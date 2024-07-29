# WPA3 Protocols & Encryption Summary

**Purpose and Context:**
The reading covers the advancements in Wi-Fi Protected Access (WPA) security, specifically the WPA3 protocol, which builds on WPA2. It explains the importance of protocols and encryption in cybersecurity, highlighting the role of WPA3 in enhancing wireless network security.

**WPA3 Overview:**
WPA3 is designed to replace WPA2, offering improved features and methods to address the security weaknesses of WPA2. The key benefits include:

- Simplified wireless security
- Stronger authentication
- Powerful encryption
- Stable business continuity
- Enhanced security methods
- Replacement for legacy protocols
- Protected Management Frames (PMF) for enterprise networks

WPA3 has two versions: WPA3-Personal and WPA3-Enterprise.

**WPA3-Personal:**
Intended for individual users and personal/home Wi-Fi networks, WPA3-Personal enhances security and user convenience. Key features include:

1. **Natural Password Selection:** Allows users to set memorable passwords.
2. **Increased Ease of Use:** Users don't need to change how they connect to Wi-Fi to benefit from improved security.
3. **Forward Secrecy:** Protects data even if the password is stolen.
4. **Simultaneous Authentication of Equals (SAE):** An improvement over the WPA2-Personal Pre-Shared Key (PSK) handshake protocol. SAE uses PSK to generate a Pairwise Master Key (PMK) and involves a complex, multi-stage process that makes it difficult for cybercriminals to intercept and use the authentication key.

SAE also reduces the chances of successful dictionary and brute force attacks and addresses key reinstallation attacks (KRACKs), which could decrypt data and expose sensitive information.

**WPA3-Enterprise:**
Designed for business networks with multiple users, WPA3-Enterprise addresses the weaknesses of WPA2-Enterprise and introduces the following improvements:

1. **Galois/Counter Mode Protocol (GCMP-256):** Uses 256-bit AES encryption, offering stronger security compared to the 128-bit encryption used in WPA2.
2. **Opportunistic Wireless Encryption (OWE):** Replaces WPA2's EAP with a system that encrypts and authenticates all wireless traffic, improving security in open networks.
3. **Wi-Fi Device Provisioning Protocol (DPP):** Uses QR codes or NFC tags for passwordless Wi-Fi access, replacing WPA2's Wi-Fi Protected Setup (WPS).
4. **384-bit Hashed Message Authentication Mode (HMAC) with Secure Hash Algorithm (SHA):** Ensures message integrity by comparing hash codes from the message origin and receiver.
5. **Elliptic Curve Diffie-Hellman Exchange (ECDHE) and Elliptic Curve Digital Signature Algorithm (ECDSA):** Provides faster and more secure key management and authentication, replacing the WPA2 4-way handshake.

**Key Takeaways:**
As technology advances and computing power increases, the need for more complex encryption algorithms will persist to stay ahead of cybercriminals. WPA3 provides significant improvements over WPA2 in terms of security and ease of use. Key features for WPA3-Personal include natural password selection, ease of use, forward secrecy, and SAE. For WPA3-Enterprise, key features include GCMP-256, OWE, DPP, 384-bit HMAC with SHA, and ECDHE/ECDSA.
