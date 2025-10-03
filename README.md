# 07-cyber-security-interns8
Understand the role of VPNs in protecting privacy and secure communication
--
1.Download and install the VPN client
--
I download a VPN on VPNBOOK, 
![image alt](https://github.com/Riplilphat38/07-cyber-security-interns8/blob/0f258e36505816fa2cfe85201c95db3eeba81de8/Screenshot%20From%202025-10-03%2021-36-32.png)

I install OPENVPN

`sudo apt update
sudo apt install openvpn`

2.Connect to a VPN server (choose closest or any location).
--

I connectbto the US server
![image alt](https://github.com/Riplilphat38/07-cyber-security-interns8/blob/0f258e36505816fa2cfe85201c95db3eeba81de8/Screenshot%20From%202025-10-03%2021-38-14.png)

3.Browse a website to confirm traffic is encrypted.
--
![image alt](https://github.com/Riplilphat38/07-cyber-security-interns8/blob/0f258e36505816fa2cfe85201c95db3eeba81de8/Screenshot%20From%202025-10-03%2021-47-42.png)

4.Disconnect VPN and compare browsing speed and IP
--
I disconnected Vpn using:
`sudo pkill openvpn`

This is my IP

![image alt](https://github.com/Riplilphat38/07-cyber-security-interns8/blob/0f258e36505816fa2cfe85201c95db3eeba81de8/Screenshot%20From%202025-10-03%2022-18-00.png)


5.VPN Encryption & PrivacyFeatures
--
Encryption Standards:

* ﻿﻿Protocols: OpenVPN (UDP/TCP), WireGuard, IKEv2/IPsec
  
* ﻿﻿Ciphers: AES-256-GCM, ChaCha20- Poly1305
  
* ﻿﻿Handshake: RSA-4096, ECDH for key exchange
  
* ﻿﻿Hashing: SHA-384 for authentication
  
Privacy Protection Layers:

1. ﻿﻿﻿IP Masking: Hides your real IP address
   
2. ﻿﻿﻿DNS Protection: Prevents DNS leaks
   
3. ﻿﻿﻿Kill Switch: Blocks traffic if VPN drops
   
4. ﻿﻿﻿No-Logs Policy: Provider doesn't store activity
   
5. ﻿﻿﻿WebRTC Protection: Prevents browser IP leaks
    
Security Features:

* ﻿﻿Perfect Forward Secrecy: New keys per session
  
* ﻿﻿Obfuscation: Stealth protocols to bypass VPN blocks

* Split Tunneling: Choose which apps use VPN
  
* ﻿﻿Multi-hop: Route through multiple servers


6. VPN Benefits and Limitations Summary
   --

Benefits:

Privacy & Anonymity:

* ﻿﻿Masks real IP address from websites and services

* ﻿﻿Prevents ISP tracking and data collection

* ﻿﻿Hides browsing activity from network observers
Security:


* ﻿﻿Encrypts all internet traffic (especially on public Wi-Fi)

* ﻿﻿Protects against man-in-the-middle attacks

* ﻿﻿Secures sensitive data transmissior

Access & Freedom:
* ﻿﻿Bypasses geographic restrictions and censorship

* ﻿﻿Access region-locked content and services

* ﻿﻿Avoids bandwidth throttling by ISPs
Additional Advantages:


* ﻿﻿Safe P2P file sharing and torrenting

* ﻿﻿Enhanced protection for remote work

* ﻿﻿Multiple server locations for optimal performance
 

Limitations:

Performance Impact:

* ﻿﻿20-50% speed reduction due to encryption overhead

* ﻿﻿Increased latency (especially with distant servers)

* ﻿﻿Potential connection instability
Trust Issues:

* ﻿﻿Must trust VPN provider with all internet traffic

* ﻿﻿Some free VPNs may log and sell user data

* ﻿﻿Legal jurisdiction affects privacy protections

Technical Challenges:

* Some websites and services block
VPN IPS

* ﻿﻿Banking and financial sites may detect and block VPNs

* ﻿﻿Configuration can be complex for nontechnical users

Legal & Compliance:


* ﻿﻿VPNs are illegal or restricted in some countries (China, Russia, UAE)

* ﻿﻿May violate terms of service streaming platforms

* ﻿﻿Potential legal issues if used for illegal activities

Not Complete Anonymity:

* ﻿﻿Doesn't protect against browser fingerprinting

* ﻿﻿Can still be tracked by cookies and online accounts

* ﻿﻿Metadata may still be visible to determined adversaries

Best Practices:

* ﻿﻿Choose reputable, no-logs VPN providers

* ﻿﻿Enable kill switch and DNS leak protection

* ﻿﻿Use WireGuard protocol for better performance

* ﻿﻿Regularly test for IP and DNS leaks

* ﻿﻿Combine with other privacy tools (Tor, privacy browsers)

Conclusion:
VPNs are essential tools for enhancing online privacy and security, but they're not silver bullets. They provide strong protection against casual surveillance and geographic restrictions, but users should maintain realistic expectations about their capabilities and limitations.
