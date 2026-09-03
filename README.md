🔐 # secure-virtual-network-architecture

## 🎯 Objective

The main objective of this project is to design and deploy a **secure, segmented virtual network infrastructure**, with security controls applied from **Layer 2 to Layer 7**.

The infrastructure is divided into **separate network zones — External, Internal, and Private —** to isolate critical resources and control communication between them.

The project aims to:

* 🔹 **Segment the network** into controlled and isolated zones.
* 🔹 **Restrict communication** between zones according to defined security policies.
* 🔹 **Protect network and system resources** through firewall and access-control mechanisms.
* 🔹 **Secure web applications** using a Web Application Firewall (WAF).
* 🔹 **Monitor and detect suspicious activity** through centralized security monitoring.

🛠️ Technologies

🖥️ Hyper-V — Virtualization

🔥 FortiGate — Firewall & network security

🛡️ SafeLine — Web Application Firewall

🐧 Ubuntu / Kali Linux — Operating systems & security testing

🌐 Apache — Web server

🗄️ MySQL — Database

🔐 Wazuh — Security monitoring & alerting

🧪 Nmap / SQLmap / SlowHTTPTest — Security testing





🏗️ Architecture




<img width="1356" height="1160" alt="NEW NEXT SETP" src="https://github.com/user-attachments/assets/645e82ef-2b60-4bac-bd8b-25e7a6bc2fb5" />


🌐 External Zone — represents external/Internet traffic.

🔒 Internal Zone — contains the Web Server and Admin VM.

🗄️ Private Zone — isolates the Database Server.

🔥 FortiGate controls traffic between the different zones.

🛡️ SafeLine inspects incoming web traffic before it reaches the Web Server.

🔐 Wazuh collects logs and monitors the virtual infrastructure.



📸 Project Screenshots


<img width="1478" height="605" alt="Capture d&#39;écran 2026-01-27 095114" src="https://github.com/user-attachments/assets/21442846-0d93-4ad9-89c3-4ffe2bdf68eb" />




<img width="787" height="515" alt="Capture d&#39;écran 2026-01-27 082132" src="https://github.com/user-attachments/assets/f67cf0f6-9751-471d-ac43-fd9a5f28737f" />





<img width="1215" height="590" alt="Capture d&#39;écran 2026-09-03 092108" src="https://github.com/user-attachments/assets/9e051ca2-fc0d-4579-95a5-40a280bdc538" />






