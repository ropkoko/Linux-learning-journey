# 🐧 Linux Troubleshooting Masterclass (Day 6)

## ☁️ Cloud Engineering Learning Journey

This project documents my Day 6 learning in Linux troubleshooting as part of my Cloud Engineering journey.  
The focus was on understanding how to diagnose, analyze, and fix Linux system issues like a real system administrator or cloud engineer.

---

# 🎯 Objective

To gain practical skills in:
- Diagnosing Linux system issues
- Monitoring system performance
- Managing processes and services
- Analyzing system logs
- Troubleshooting network problems
- Fixing common server failures

---

# 🧠 What I Learned

## 🔵 1. System Diagnostics

I learned how to check system health and performance.

### Commands used:
```bash
top
htop
uptime

Key insights
* CPU usage shows system load
* Memory usage helps detect system overload
* Load average shows system stress

🔵 2. Memory & Disk Analysis

I learned how to check system resource usage.

Commands used:
free -h
df -h
du -sh *

Key insights
* Low memory causes system slowdown
* Full disk can break services and SSH access
* Large files often cause storage issues

🔵 3. Process Management

I learned how to manage running processes.

Commands used:

ps aux
ps aux | grep apache
kill -9 <PID>

Key insights:
* Every running program is a process
* High CPU processes can crash systems
* Processes can be stopped using PID

🔵 4. Service Troubleshooting (systemd)

I learned how to manage Linux services.

Commands used:
systemctl status ssh
systemctl status apache2
systemctl start apache2
systemctl restart ssh
systemctl enable apache2

Key insights:
* Services must be running for applications to work
* systemctl is used to control system services
* Failed services are a common production issue

🔵 5. Log Analysis (VERY IMPORTANT)

I learned how to debug using logs.

Commands used:
* journalctl
* journalctl -xe
* journalctl -u ssh
* journalctl -f

Key insights:
* Logs show real system errors
* Most Linux problems are solved using logs
* journalctl is critical for debugging services
🔵 6. Network Troubleshooting

I learned how to debug network issues.

Commands used:
* ip a
* ping google.com
* ss -tulnp
* curl http://localhost

Key insights:
* IP configuration affects connectivity
* DNS issues can break internet access
* Open ports determine service availability

🧪 Practical Lab Work
✔ Simulated system issues and fixes:
* Stopped a service and restarted it
* Identified high CPU processes
* Checked disk usage and memory usage
* Diagnosed network connectivity issues
* Analyzed system logs for errors

🧰 Tools Used
* top / htop → system monitoring
* free → memory analysis
* df → disk usage
* ps → process management
* systemctl → service control
* journalctl → log analysis
* ping / ss → network debugging

🔥 Key Troubleshooting Flow I Learned

When a system breaks, I now follow this approach:

* Check system health (CPU, RAM, disk)
* Check running processes
* Check service status
* Read system logs
* Check network connectivity
* Fix the root cause

💡 Real Cloud Engineering Insight

This lab reflects real-world cloud engineering tasks such as:

* Debugging server downtime
* Fixing broken services
* Monitoring cloud VM performance
* Investigating system failures
* Handling production incidents

🚀 Outcome

After completing this lab, I can now:

* Diagnose Linux system issues confidently
* Troubleshoot server failures
* Analyze logs effectively
* Manage Linux services
* Debug network problems
* Understand real-world cloud server behavior
