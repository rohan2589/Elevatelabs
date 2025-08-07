# Internship Task1

# 🔍 Nmap Network Scan Report (192.168.0.1)

This project documents a TCP SYN network scan conducted using **Nmap v7.95** on the IP '192.168.0.1'. The scan identifies active hosts, their open ports, and the associated services.

---

## 🛠️ Tools Used

- **Nmap Version:** 7.95  
- **Scan Type:** TCP SYN Scan
- **Machine:** Kali Linux  
- **Output Format:** Normal (`-oN result.txt`)

---

## 🚀 Command Used

```bash
nmap -sS 192.168.0.1
```
![Screenshot ](https://github.com/rohan2589/Elevatelabs/blob/main/Nmap.JPG)

---

## 🧾 Scan Summary

---

### 🔹 Host: `192.168.0.1`
- **Status:** Host is up (0.0025s latency)
- **MAC Address:** E4:C3:2A:90:FE:FE
- **Open Ports:**
  | Port  | State | Service   |
  |-------|-------|-----------|
  | 22    | open  | ssh       |
  | 53    | open  | domain    |
  | 80    | open  | http      |
  | 443   | open  | https     |
  | 1900  | open  | upnp      |

---

## 💾 Saving Result in txt format

```bash
nmap -sS 192.168.0.1 -oN result.txt

```
