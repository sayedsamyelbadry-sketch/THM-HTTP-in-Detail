# 🌐 TryHackMe – HTTP in Detail Write-up

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen)
![Category](https://img.shields.io/badge/Category-Web%20Fundamentals-blue)
![Platform](https://img.shields.io/badge/Platform-TryHackMe-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📝 Overview

**HTTP in Detail** is a foundational TryHackMe room that introduces the HTTP/HTTPS protocols and explains how web communication works. The room covers HTTP requests and responses, methods, status codes, headers, cookies, and practical request manipulation.

---

# 🧪 Lab Information

| Parameter | Details |
|------------|---------|
| **Room Name** | HTTP in Detail |
| **Platform** | TryHackMe |
| **Category** | Web Fundamentals |
| **Difficulty** | Easy |
| **Tasks** | 7 |

---

# 🎯 Task Solutions

## Task 1 – What is HTTP?

| Question | Answer |
|----------|--------|
| HTTP stands for | HyperText Transfer Protocol |
| HTTPS "S" stands for | Secure |
| Flag | `THM{INVALID_HTTP_CERT}` |

---

## Task 2 – Requests & Responses

| Question | Answer |
|----------|--------|
| HTTP Version | `HTTP/1.1` |
| Response header indicating content size | `Content-Length` |

---

## Task 3 – HTTP Methods

| Action | Method |
|--------|--------|
| Create a user | `POST` |
| Update email | `PUT` |
| Delete uploaded picture | `DELETE` |
| View a webpage | `GET` |

---

## Task 4 – Status Codes

| Scenario | Status Code |
|----------|------------|
| Resource Created | `201 Created` |
| Page Not Found | `404 Not Found` |
| Service Unavailable | `503 Service Unavailable` |
| Unauthorized Access | `401 Unauthorized` |

---

## Task 5 – HTTP Headers

| Purpose | Header |
|---------|--------|
| Browser information | `User-Agent` |
| Returned content type | `Content-Type` |
| Requested website | `Host` |

---

## Task 6 – Cookies

| Question | Answer |
|----------|--------|
| Header used to store cookies | `Set-Cookie` |

---

## Task 7 – Making HTTP Requests

| Request | Flag |
|---------|------|
| GET `/room` | `THM{YOU'RE_IN_THE_ROOM}` |
| GET `/blog?id=1` | `THM{YOU_FOUND_THE_BLOG}` |
| DELETE `/user/1` | `THM{USER_IS_DELETED}` |
| PUT `/user/2` (`username=admin`) | `THM{USER_HAS_UPDATED}` |
| POST `/login` (`thm : letmein`) | `THM{HTTP_REQUEST_MASTER}` |

---

# 🛠️ Tools Used

- Browser
- TryHackMe AttackBox
- cURL

---

# 📚 Key Concepts Learned

- HTTP vs HTTPS
- HTTP Request & Response Structure
- HTTP Methods (GET, POST, PUT, DELETE)
- HTTP Status Codes
- HTTP Headers
- Cookies & Session Management
- Request Manipulation

---

# 💡 Key Takeaways

- HTTP is the foundation of web communication.
- HTTPS secures communication using TLS encryption.
- Understanding HTTP methods and status codes is essential for web penetration testing.
- Headers and cookies play a critical role in authentication and session management.
- Strong HTTP knowledge is fundamental for identifying vulnerabilities such as IDOR, Authentication flaws, CSRF, and Broken Access Control.

---

## 🏷️ Tags

`HTTP` `HTTPS` `Web Security` `Web Fundamentals` `TryHackMe` `Cybersecurity` `Pentesting` `Burp Suite` `API Security`
