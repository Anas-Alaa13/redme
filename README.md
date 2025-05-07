
#  Introduction to Networking & HTTP Protocol

This short session covers the **basics of computer networking** and introduces the **HTTP protocol**, one of the most widely used protocols on the internet.  

---

## What is a Network?

A **network** is a group of two or more devices (computers, phones, printers, etc.) connected together to **share data or resources**.

- Allows file sharing, internet access, and communication.
- Example: Your home Wi-Fi network connects your phone, laptop, and smart devices.

---

##  Common Types of Networks:

| Type | Description | Example |
|------|-------------|---------|
| **LAN** | Local Area Network – connects devices in a small area. | Home, school, office |
| **WAN** | Wide Area Network – connects devices over large distances. | The Internet |

---

##  Network Layers (OSI Model - Simplified)

The **OSI Model (Open Systems Interconnection)** is a conceptual framework that explains **how data travels from one device to another over a network**.  
It consists of **7 layers**, and each layer has a specific role.  
This model helps us **understand and troubleshoot networks in an organized way**.

###  1. Physical Layer
- This is the **lowest and most basic layer**.
- It deals with the **physical medium** of data transmission like cables, electrical signals, or radio waves.
- Examples: Ethernet cables, Wi-Fi signals, fiber optics.

###  2. Data Link Layer
- Responsible for **direct communication between devices** on the same local network.
- Uses **MAC addresses** to identify devices.
- Example: A computer connected to a network switch.

###  3. Network Layer
- Manages **routing** — how data travels between networks.
- Uses **IP addresses** to deliver packets from one device to another across the internet.
- Main protocol: **IP (Internet Protocol)**.

###  4. Transport Layer
- Ensures that data is **delivered accurately and in order**.
- Key protocols:
  - **TCP**: Reliable, checks for errors and retransmits lost data.
  - **UDP**: Faster, but doesn’t guarantee delivery.
- Example: TCP is used for downloading a file; UDP for live video streaming.

###  5. Session Layer
- Manages **sessions** — ongoing connections between devices.
- Ensures sessions start, stay active, and close properly.
- Example: Maintaining a Zoom call or logging into a remote server.

###  6. Presentation Layer
- Translates data between the application layer and the network.
- Handles **encryption, decryption, and data formatting**.
- Examples: JPEG image conversion, SSL encryption, data compression.

###  7. Application Layer
- Closest to the **end user**.
- Provides services and interfaces that applications use to access the network.
- Examples of protocols:
  - **HTTP** – for web browsing
  - **DNS** – for domain name resolution

###  Real-life Example (Top to Bottom):

When you open a website:

1. **Application Layer** – Your browser sends an HTTP request.
2. **Transport Layer** – TCP ensures the request arrives correctly.
3. **Network Layer** – IP handles routing to the server.
4. **Data Link & Physical Layers** – The request travels through cables or Wi-Fi to reach the destination.

---

##  What is HTTP?

**HTTP (HyperText Transfer Protocol)** is the protocol used by browsers to communicate with web servers.

### How HTTP Works:
1. You enter `www.example.com` in your browser.
2. The browser sends an **HTTP Request** to the server.
3. The server responds with an **HTTP Response** (usually HTML content).
4. The browser renders the web page.

###  Common HTTP Methods:
- `GET`: Retrieve data (like a webpage).
- `POST`: Send data (like submitting a form).
- `PUT`, `DELETE`: Modify or remove data.

### HTTP vs HTTPS:
- **HTTP**: Plain text communication.
- **HTTPS**: Encrypted using SSL/TLS for security.

---

## In Conculusion:
-Networks are the infrastructure for everything on the internet.

-HTTP is the gateway that makes websites work.

-Understanding these things is important for anyone interested in technology or programming.
---

