# Mini Project: Star Topology with a switch

## 📌 Project Overview
This project demonstrates the the use of star topology when connecting 4 PC's in a small office

All 4 PC's are configured with static IP addresses in the **same subnet**, allowing them to successfully communicate via ICMP ping.

---

## 🏗️ Topology
![Topology Diagram]<img width="1920" height="2088" alt="Star Topology" src="https://github.com/user-attachments/assets/098b3480-99e7-4dee-85e5-23cc6aebd28e" />


- **PC-A**: 192.168.39.5 / 255.255.255.0  
- **PC-B**: 192.168.39.6 / 255.255.255.0
- **PC-C**: 192.168.39.7 / 255.255.255.0  
- **PC-D**: 192.168.39.8 / 255.255.255.0    
- Connection: **Copper /straight through** cable
- **Main-Switch**: 2960 Switch

---

## ⚙️ Device Configuration
### PC-A
![PC-A IP Configuration]
<img width="1103" height="1115" alt="PC-A IP Config" src="https://github.com/user-attachments/assets/4ec6960b-e997-4cbb-901b-0266268b4f27" />

### PC-B
![PC-B IP Configuration]
<img width="1103" height="1115" alt="PC-B IP Config" src="https://github.com/user-attachments/assets/c13cb9bf-0bdc-469d-ab9f-edb3d92a5329" />

### PC-C
![PC-C IP Configuration]
<img width="1103" height="1115" alt="PC-C IP Config" src="https://github.com/user-attachments/assets/e35b56fa-6b2a-4ab9-a04f-a99c28a692ec" />

### PC-D
![PC-D IP Configuration]
<img width="1103" height="1115" alt="PC-D IP Config" src="https://github.com/user-attachments/assets/c22157b0-5f75-4382-ad5f-da32562b1290" />

---

## 🧪 Testing
Communication verified using **ping** from PC-A to PC-D, from PC-A to PC-C, and from PC-A to PC-B:

![Successful Ping]
<img width="1103" height="1115" alt="Successful Ping Tests" src="https://github.com/user-attachments/assets/c720a11a-fad2-407b-a94c-e987326664bd" />


**Result:** Replies received, proving that devices in the same subnet can exchange data when connected properly.

---

## 🎯 Learning Objectives
- Understand the concept of a **Star Topology** between several hosts.  
- Configure **static IP addressing** within the same subnet.  
- Verify communication using the **ping utility**.  
  

---

## 📂 Files
- [`Star-Topology.pkt`](Star-Topology.pkt) – Packet Tracer project file  
- Screenshots in `/images` folder  
- `README.md` (this documentation)
