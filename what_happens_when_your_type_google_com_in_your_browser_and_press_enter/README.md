
```markdown
# 🌐 What Happens When You Type https://www.google.com in Your Browser and Press Enter

A deep dive into the complete lifecycle of a web request, from DNS resolution to browser rendering.

# What Happens When You Type https://www.google.com in Your Browser and Press Enter

## Project Overview

This project explores the complete journey of a web request when a user types:

https://www.google.com

into a web browser and presses **Enter**.

The goal is to understand how different layers of modern web infrastructure work together to deliver a web page, including networking, security, servers, databases, and browser rendering.

This project is part of the **Holberton School System Engineering & DevOps curriculum** and focuses on explaining the full request lifecycle from the client to the server and back.

---

## Learning Objectives

By completing this project, I learned about:

- DNS resolution
- TCP/IP communication
- TCP three-way handshake
- HTTPS and TLS/SSL encryption
- Firewalls
- Load balancers
- Web servers
- Application servers
- Databases
- Browser rendering process
- Modern web infrastructure architecture

---

## Project Structure

```text
what_happens_when_your_type_google_com_in_your_browser_and_press_enter/
├── README.md
├── 0-blog_post
└── 1-what_happen_when_diagram
````
Tasks
Task 0 — Blog Post

Write a detailed technical article explaining what happens when a user types:

https://www.google.com

and presses Enter.

The article covers:

DNS Request
TCP/IP
Firewall
HTTPS / SSL / TLS
Load Balancer
Web Server
Application Server
Database

The article was published on Medium/LinkedIn.

Task 1 — Infrastructure Diagram

Create an infrastructure diagram illustrating the complete flow of a web request.

The diagram includes:

DNS Resolution
HTTPS Communication
Firewall Inspection
Load Balancer Distribution
Web Servers
Application Servers
Database Servers
Response Flow back to the Browser
Request Flow Summary

The following sequence describes the lifecycle of a request:

User enters the URL in the browser.
Browser performs DNS resolution.
Domain name is translated into an IP address.
TCP three-way handshake establishes a connection.
TLS/SSL handshake secures the communication.
Request passes through a firewall.
Load balancer selects an available backend server.
Web server receives the request.
Application server executes business logic.
Database retrieves required data.
Application server generates the response.
Response is returned through the web server.
Browser renders the page for the user.
Technologies and Concepts
DNS (Domain Name System)

Converts human-readable domain names into IP addresses.

Example:

www.google.com → 142.250.x.x
TCP/IP

Provides reliable communication between client and server.

Uses the TCP Three-Way Handshake:

SYN
SYN-ACK
ACK
HTTPS / TLS

Encrypts communication between client and server.

Provides:

Confidentiality
Integrity
Authentication
Firewall

Filters incoming and outgoing network traffic.

Protects servers from unauthorized access and malicious requests.

Load Balancer

Distributes traffic across multiple servers.

Benefits:

High Availability
Fault Tolerance
Scalability
Web Server

Examples:

Nginx
Apache

Responsibilities:

Serve static files
Handle HTTP requests
Reverse proxy traffic
Application Server

Processes dynamic content and business logic.

Examples:

Python
Node.js
Java
PHP
Database

Stores application data.

Examples:

MySQL
PostgreSQL
MongoDB

Used for:

User information
Search results
Application data
Architecture Overview
Client
   │
   ▼
DNS Resolution
   │
   ▼
Firewall
   │
   ▼
HTTPS/TLS
   │
   ▼
Load Balancer
   │
   ▼
Web Server
   │
   ▼
Application Server
   │
   ▼
Database
   │
   ▼
Response
   │
   ▼
Browser Rendering
````
Author

SARA REBATI
Holberton School — System Engineering & DevOps

References
DNS Documentation
TCP/IP Model
TLS/SSL Documentation
Nginx Documentation
HAProxy Documentation
MySQL Documentation
Google Web Fundamentals
