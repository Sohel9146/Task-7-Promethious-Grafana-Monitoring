<h1 align="center">📊 Grafana Monitoring Dashboards</h1>

<p align="center">
A complete and professional Grafana setup for monitoring CPU, Memory, Disk, Network, Docker Containers, and Virtual Machines in real time.
</p>

---

## 🌟 Highlights

✅ Real-Time Metrics – CPU, Memory, Disk, Network  
✅ Docker Insights – Container-level stats  
✅ VM Monitoring – Virtual Machine resource usage  
✅ Kiosk Mode – Perfect for presentations and NOC screens  

---

## 📂 Folder Structure

```bash
Task-7-Promethious-Grafana-Monitoring/
│
├── screenshots/               # Dashboard screenshots
│   ├── 1 - Prometheus Targets Page
│   ├── 2 - Grafana – Node Exporter Full Dashboard (ID 1860) Overview
│   ├── 3 - Grafana – CPU & Memory Panels
│   ├── 4.1 - Grafana – Storage-Disk
│   ├── 4.2 - Grafana – Storage-Disk
│   ├── 5 - Grafana – File-Disk 
│   ├── 6.1 - Network Panel
│   ├── 6.2 - Network Panel
│   ├── 7 - Docker Containers Panel 
│
└── README.md
```

---

## 🖼 Screenshot Previews



### **1 - Prometheus Targets Page**
![1 - Prometheus Targets Page](screenshots/1%20-%20Prometheus%20Targets%20Page.png) 

### **2 - Grafana – Node Exporter Full Dashboard (ID 1860) Overview**
![2 - Grafana – Node Exporter Full Dashboard (ID 1860) Overview](screenshots/2%20-%20Grafana%20–%20Node%20Exporter%20Full%20Dashboard%20(ID%201860)%20Overview.png) 

### **3 - Grafana – CPU & Memory Panels**
![3 - Grafana – CPU & Memory Panels](screenshots/3%20-%20Grafana%20–%20CPU%20&%20Memory%20Panels.png) 

### **4.1 - Grafana – Storage-Disk**
![4.1 - Grafana – Storage-Disk](screenshots/4.1%20-%20Grafana%20–%20Storage-Disk%20.png) 

### **4.2 - Grafana – Storage-Disk**
![4.2 - Grafana – Storage-Disk](screenshots/4.2%20-%20Grafana%20–%20Storage-Disk.png) 

### **5 - Grafana – File-Disk**
![5 - Grafana – File-Disk ](screenshots/5%20-%20Grafana%20–%20File-Disk%20.png) 

### **6.1 - Network Panel**
![6.1 - Network Panel](screenshots/6.1%20-%20Network%20Panel.png) 

### **6.2 - Network Panel**
![6.2 - Network Panel](screenshots/6.2%20-%20Network%20Panel.png) 

### **7 - Docker Containers Panel**
![7 - Docker Containers Panel](screenshots/7%20-%20Docker%20Containers%20Panel%20.jpeg) 



---

## 🚀 Quick Setup Guide

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/Sohel9146/Task-7-Promethious-Grafana-Monitoring.git
cd Task-7-Promethious-Grafana-Monitoring
```

### **2️⃣ Import the Dashboard**
- Open **Grafana → Dashboards → Manage → Import**
- Paste the dashboard ID from Grafana.com (example: **1860** for Node Exporter, **193** for Docker Monitoring)
- Click **Load**, then choose your Prometheus data source, and click **Import**

### **3️⃣ Configure Data Sources**
- Go to **Settings → Data Sources**
- Click **Add Data Source**
- Select **Prometheus**
- Set the URL to your Prometheus server (e.g., http://localhost:9090)
- Click **Save & Test**

### **4️⃣ View in Kiosk Mode**
- Click the **kiosk icon** in Grafana for distraction-free viewing

---

## 🎯 Project Outcomes

By completing this setup, you will:
- Have a **ready-to-use professional Grafana dashboard**
- Gain **full visibility** over system performance
- Monitor **Docker containers & VMs** in real time
- Present monitoring data effectively in **meetings or reports**

---

## ✍️ Author

**Sohel**  
💼 DevOps & Monitoring Enthusiast  
🔗 [GitHub Profile](https://github.com/Sohel9146)  
📧 suhailshaikh7866@gmail.com  

---


