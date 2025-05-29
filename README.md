# 🔍 Nmap Local Network Port Scan – Internship Task

This project is part of my internship assignment focused on **cybersecurity**. The goal is to **discover open ports on devices in a local network** using `Nmap`, understand what services are exposed, and analyze potential security risks.

---

## 🎯 Objective

- Scan the local network to identify **active hosts**.
- Discover **open TCP ports** on each host.
- Analyze the services running on those ports.
- Identify potential **vulnerabilities or misconfigurations**.

---

## 🧰 Tools Used

- **Nmap** – for scanning devices and ports.
- **Wireshark** *(optional)* – for packet-level inspection.
- **GitHub** – to document and present findings.

---

## 🧪 Steps Performed

1. **Installed Nmap** from the official site.
2. Identified my local IP range: `192.168.29.0/24`
3. Ran a TCP SYN scan with the command: nmap -sS 192.168.29.0/24 
4. Noted active devices and open ports.
5. Analyzed results and researched the services running on those ports.
6. Documented everything in `report.md`.

---

## 📁 Files in This Repository

| File Name         | Description                                      |
| `scanresults.txt`| Raw output of the Nmap scan                      |
| `report.md`      | Human-readable explanation of the findings       |
| `README.md`      | Overview of the project and process              |

---

## 📌 Key Findings

- Detected devices exposing ports like `80`, `443`, `8080`, `135`, and others.
- Possible services identified: **HTTP**, **HTTPS**, **Samba**, **UPnP**, and more.
- Highlighted potential risks mentioned in `report.md`, such as misconfigured services or unnecessary exposed ports.

---

## ✅ Conclusion

This project helped me gain hands-on experience with **network reconnaissance** and understand the importance of minimizing attack surfaces. Tools like Nmap are vital in securing networks by revealing hidden exposures.

---

## 🙋‍♀️ About Me

**Swaranjali**  
Second-year B.Tech student (Electronics and Communication Engineering)  
Internship Role: Cyber Security Analyst
