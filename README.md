# 🌐 AWS Site-to-Site VPN Configuration Project (UMGC – CMIT 265)

A hands-on cloud networking project where I built a secure Site-to-Site VPN on AWS, connecting an on-premises network to an Amazon Virtual Private Cloud (VPC) using IPSec tunnels, Virtual Private Gateways, and Customer Gateways.

👉 **Full Lab Report with screenshots and detailed steps:**  
[Click here to view the complete project documentation](https://github.com/Pelumi-Johnson/Creating-a-Site-to-Site-VPN-on-AWS/blob/main/Name_%20Pelumi%20Johnson_University%20of%20Maryland%20Global%20Center.pdf)

---

## 🎯 Objective
This project simulates how real organizations extend their private networks into the cloud. By completing this lab, I gained experience configuring:

• A Virtual Private Gateway (VGW)  
• A Customer Gateway (CGW)  
• An IPSec-based Site-to-Site VPN  
• Secure encrypted communication between AWS and an external network  

It strengthened my understanding of routing, tunneling, encryption, and cloud networking fundamentals.

---

## 🛠️ Technologies Used
• ☁️ AWS Console  
• 🛰️ Amazon VPC  
• 🔒 Virtual Private Gateway (VGW)  
• 🧱 Customer Gateway (CGW)  
• 🔐 IPSec VPN Tunnels  

---

## 🚀 Project Overview

### 1️⃣ Virtual Private Gateway Creation  
Configured a VGW inside AWS to act as the cloud endpoint for the VPN connection.

### 2️⃣ Customer Gateway Setup  
Created a Customer Gateway representing an on-premises router with a designated public IP.

### 3️⃣ Site-to-Site VPN Configuration  
Built an IPSec VPN using the VGW and CGW, completing all authentication and tunnel configuration parameters.

### 4️⃣ Tunnel Options and Security Keys  
Customized tunnel settings, inside CIDR ranges, and pre-shared keys for secure encrypted communication.

### 5️⃣ Successful Deployment  
Verified that the VPN connection was created successfully and registered properly inside AWS VPC.

All screenshots and step-by-step explanations appear in the linked lab report above.

---

## 📘 Key Concepts Learned

### 🧠 Site-to-Site VPN  
A secure tunnel that links remote networks as if they were on the same LAN.

### 🔐 IPSec  
Handles encryption, authentication, and secure transmission of network data.

### 🧱 Gateway Architecture  
• **VGW** = AWS VPN endpoint  
• **CGW** = On-premises router representation  

### 🌉 Tunnel Inside CIDR  
Special-purpose subnets used strictly for VPN endpoint communication.

---

## 🧠 Lessons Learned
• I strengthened my ability to configure secure VPN tunnels in AWS.  
• I learned how organizations integrate cloud networks with on-premises environments.  
• I gained hands-on familiarity with IPSec, gateway authentication, and cloud routing.

---

## 🏁 Project Summary
Created a fully functional AWS Site-to-Site VPN by configuring a Virtual Private Gateway, Customer Gateway, and IPSec tunnels. This project demonstrates foundational cloud networking skills used in real corporate environments.

---


