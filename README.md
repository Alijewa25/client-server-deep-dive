#  Web Systems Architecture & Development Lifecycle
### *A Deep Technical Analysis of Internet Infrastructure and Application Delivery*

<p align="center">
  <img src="https://img.shields.io/badge/Holberton-PLD-red?style=for-the-badge" alt="Holberton PLD">
  <img src="https://img.shields.io/badge/Focus-System_Design-blue?style=for-the-badge" alt="System Design">
  <img src="https://img.shields.io/badge/Status-Documentation-green?style=for-the-badge" alt="Documentation">
</p>

---

## 📖 Project Overview
This project explores the behind-the-scenes logic of modern web systems. We aren't just talking about writing code; we are discussing how software operates as a unified system with hardware, network protocols, and infrastructure.The goal is to deeply understand the entire chain, from high-level programming languages to complex network requests.

---

## Knowledge Map (Navigation)

You can use the links below to dive deep into each section:

1. [**Languages**](./languages.md) & [**Frameworks**](./frameworks.md) – Why is one language not enough, and how are frameworks born?
2. [**Servers & Infrastructure**](./servers.md) – "Service Providers," ports, and hardware logic.
3. [**Local Development**](./local_development.md) – The safe sandbox: `localhost` and the port system.
4. [**Deployment Strategies**](./deployment.md) – The gateway to the world: FTP, CI/CD, and Cloud.
5. [**DNS Hierarchy**](./dns.md) – The digital phonebook of the internet and query graphs.
6. [**Service Interaction**](./service_interaction.md) – APIs, REST, WebSockets, and Message Brokers.

---

## Technical Module Summaries

### 1. Specialization of Tools
Programming languages are tools. **C/C++** is built for hardware-level performance, while **Python** is created for fast and readable solutions. **JavaScript** is the only "native" language understood by web browsers.

### 2. Client-Server Model
A server is not just a computer; it is software that listens to specific ports. When a request arrives, the system decides: should it send a file, execute code, or deny access? 

### 3. DNS and IP System
DNS translates human-readable names (URLs) into machine-readable numbers (IP addresses).This is a hierarchical process involving Root, TLD, and Authoritative servers.

### 4. Automated Deployment
In the modern world, we no longer upload files to a server manually. Thanks to **CI/CD** (e.g., GitHub Actions), the system automatically tests and sends our code to the live site (Production) the moment we "push" it.

---

##  System Interaction (Workflow)
Every web operation is a cycle:
1. **Request**: The Client (user) requests information (e.g., a `POST` login request).
2. **Logic**: The Backend server processes the data and, if necessary, queries the Database.
3. **Result**: The Database returns the result, and the Backend packages it to deliver as a JSON response to the user.

---

##  Author
**Tahmina Aliyeva**
*Holberton School - Peer Learning Day (PLD)*

---
<p align="center">
  <i>"Programming languages are tools... you can't build all systems with only one language." </i>
</p>
