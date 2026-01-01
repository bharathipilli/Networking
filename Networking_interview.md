# Networking & Security – Interview Notes

---

## 1. Name two technologies used to connect two offices in remote locations.

**Answer:**
Two commonly used technologies are:
- **VPN (Virtual Private Network)**
- **Cloud Computing**

---

## 2. What is Internetworking?

**Answer:**
Internetworking is the process of connecting two or more independent networks to form a larger network.

- Networks may be public, private, commercial, industrial, or governmental.
- Intermediary devices such as **routers** or **gateways** are used.
- The interconnected network functions as a single large network.

---

## 3. Name the User Support Layers in the OSI model.

**Answer:**
The user support (software) layers are:
- Application Layer
- Presentation Layer
- Session Layer

---

## 4. Name the Network Support Layers in the OSI model.

**Answer:**
The network support (hardware) layers are:
- Network Layer
- Data Link Layer
- Physical Layer

---

## 5. What is HTTPS?

**Answer:**
HTTPS stands for **Hypertext Transfer Protocol Secure**.

- Secure version of HTTP
- Uses **SSL/TLS encryption**
- Ensures data confidentiality and integrity

**Default Port:** `443`

---

## 6. What services are provided by the Application Layer?

**Answer:**
Application layer services include:
- Mail services
- Directory services
- File transfer
- Access management
- Network virtual terminal

---

## 7. In which OSI layers are headers and trailers added?

**Answer:**
- **Headers** are added from **Application Layer (7) to Network Layer (3)**
- **Trailer** is added at the **Data Link Layer (2)**

---

## 8. What happens to data when it moves from lower to upper layers in OSI?

**Answer:**
As data moves upward:
- Headers and trailers are **removed**
- This process is called **decapsulation**

---

## 9. What happens to data when it moves from upper to lower layers in OSI?

**Answer:**
As data moves downward:
- Headers (and trailers) are **added**
- This process is called **encapsulation**
- Control and addressing information is attached

---

## 10. What is a Zone-Based Firewall (ZBF)?

**Answer:**
A Zone-Based Firewall is an advanced **stateful firewall** that controls traffic between different security zones.

It maintains a state table containing:
- Source IP
- Destination IP
- Source port
- Destination port

Only legitimate return traffic is allowed.

**Cisco Firewall Technologies:**
- CBAC (Context-Based Access Control)
- Zone-Based Firewall (ZBF)

---

## 11. What is a Server Farm?

**Answer:**
A server farm is a collection of interconnected servers located in the same physical location.

- Provides combined computing power
- Runs applications and services simultaneously

**Also called:**
- Server cluster
- Computer ranch

---

## 12. Name the three means of user authentication.

**Answer:**
The three authentication factors are:
1. **Something you know** – Password
2. **Something you have** – Token or smart card
3. **Something you are** – Biometrics

Using two factors together is called **Two-Factor Authentication (2FA)**.

---

## 13. What is the CIA Triad?

**Answer:**

### Confidentiality
- Prevents unauthorized access to data

### Integrity
- Ensures data accuracy
- Prevents unauthorized modification

### Availability
- Ensures data is accessible when needed
- Attacks like **DoS** affect availability

---

## 14. What is a VPN?

**Answer:**
VPN stands for **Virtual Private Network**.

- Creates a secure encrypted tunnel over a public network
- Allows secure remote access to private networks

---

## 15. What is Symmetric and Asymmetric Encryption?

**Answer:**

### Symmetric Encryption
- Uses a single key
- Faster
- Key distribution is difficult

### Asymmetric Encryption
- Uses public and private keys
- More secure
- Slower than symmetric encryption

---

## 16. At which OSI layer does IPsec operate?

**Answer:**
IPsec operates at the **Network Layer (Layer 3)**.

---

## 17. What is Tunnel Mode?

**Answer:**
Tunnel mode:
- Encrypts the **entire IP packet**
- Used between gateways
- Common in **site-to-site VPNs**

---

## 18. What is a Digital Signature?

**Answer:**
A digital signature ensures:
- Authenticity
- Integrity
- Non-repudiation

It verifies that the message is from a trusted sender and has not been altered.

---

## 19. What is Authorization?

**Answer:**
Authorization determines:
- What resources a user can access
- What actions a user can perform

It occurs **after authentication**.

---

## 20. Difference between IPS and Firewall

**Answer:**

### Intrusion Prevention System (IPS)
- Detects and blocks malicious activity
- Works in real time
- Provides deep packet inspection

### Firewall
- Filters traffic based on rules
- Allows or blocks traffic
- Focuses on access control

---

