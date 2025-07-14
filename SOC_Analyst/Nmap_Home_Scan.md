# 🧠 Nmap Scan Report: Home Network

📅 **Date:** `2025–07–14`  
📍 **Target:** `192.168.1.0/24`

---

## 🛠️ Scan Commands Used

```bash
nmap -sn 192.168.1.0/24          # Ping scan — discover live hosts
nmap -sV -O 192.168.1.X          # Service & OS detection for each host
nmap -p- -T4 192.168.1.X         # Full port scan with aggressive timing
```

---

✏️ **Replace `192.168.1.X` with each discovered host IP**

---

## 💻 Detected Devices

| IP Address    | MAC Address         | Hostname         | Open Ports   | Notes            |
|---------------|---------------------|------------------|--------------|------------------|
| 192.168.1.1   | xx:xx:xx:xx:xx:xx   | router.local     | 80, 443      | Default Gateway  |
| 192.168.1.10  | xx:xx:xx:xx:xx:xx   | smart-tv.local   | 8008, 8443   | Chromecast       |

---

## 📌 Observations

- **Total devices found:** 2  
- **Potential vulnerable services:** TBD

### Recommendations:

- Disable unused services  
- Update router firmware  
- Segment IoT devices (optional)

---

## 🧩 Notes

_(Write here any issues, reflections, or questions you had during the scan)_
