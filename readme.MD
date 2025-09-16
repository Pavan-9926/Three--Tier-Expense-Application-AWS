# Manual 3-Tier Deployment: Foundational Learning Project  

## 💡 Why Manual First?  
In DevOps, automation is essential — but **understanding manual deployment first is critical**.  
Building systems from the ground up strengthens troubleshooting skills and ensures automation is purposeful, not just script execution.  

---

## 🏗️ Core Architecture  
- **Frontend:** Nginx → serves static web content  
- **Backend:** Node.js → powers application logic & APIs  
- **Database:** MySQL → manages and stores application data  

---

## 🔍 Key Commands  
- **Service Management:**  
  `systemctl status <service>` | `systemctl restart <service>`  

- **Connectivity Checks:**  
  `telnet <DB_IP> 3306` | `ps -ef | grep <service>` | `netstat -lntp`  

- **Log Inspection:**  
  - Nginx → `/var/log/nginx/access.log` & `/var/log/nginx/error.log`  
  - Backend → `journalctl -u <service>`  

---

## 🧠 Key Learnings  
✨ **Deep Understanding:** Manual setup reveals how layers interconnect  
✨ **Better Troubleshooting:** Clear insight enables faster issue resolution  
✨ **Confident Automation:** Provides a strong base for tools like Ansible, Terraform, and Jenkins  

---

