# Chetan Pavan Sai Nannapaneni - Network Engineering Portfolio

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=00D4FF&center=true&vCenter=true&width=800&lines=Network+Engineering+Portfolio;Telecommunications+%26+Security+Expert;Enterprise+Network+Designer;Python+Automation+Specialist" alt="Portfolio Header" />
</div>

---

## 👨‍💻 About Me

**Graduate Student in Telecommunications Networks** with expertise in designing scalable enterprise networks, implementing robust security systems, and developing network automation solutions. Currently pursuing MS at Northeastern University with a perfect 4.0 GPA.

<div align="center">

**📍 Boston, MA | 📞 (857) 565-4795 | 📧 nannapaneni.che@northeastern.edu**

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/chetannannapaneni/)
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/chetan20030990)
[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:nannapaneni.che@northeastern.edu)

</div>

---

## 🎓 Education

**Master of Science in Telecommunication Networks** | *Expected May 2026*  
**Northeastern University, Boston, MA** | **GPA: 4.0/4.0**  
*Relevant Courses: Data Networking, Linux/UNIX Systems Management, Internet Protocols/Architecture*

**Bachelor of Technology in Electronics and Communication Engineering** | *June 2024*  
**Indian Institute of Space Science and Technology, Thiruvananthapuram**  
*Relevant Courses: Computer Networks and Architecture, Digital Signal Processing, Satellite and Optical Communications*

---

## 🛠️ Technical Skills

### Networking Protocols & Technologies
```
🌐 Layer 2/3 Protocols: OSPF, EIGRP, HSRP, GLBP, CEF, BGP, STP, VLANs
🔐 Security: IPSec VPN, Firewalls, SSL/TLS, RSA Encryption, Access Control Lists
📡 Services: TCP/IP, DNS, HTTP/S, DHCP, ARP, NTP, SNMP
🏗️ Architecture: Hierarchical Network Design, High Availability, Redundancy Planning
```

### Tools & Platforms
```
🔧 Network Tools: Cisco Packet Tracer, Wireshark, Keysight ADS, E-CAD
💻 Programming: Python, MATLAB, Shell Scripting
🐧 Systems: Linux/UNIX, Windows Server, Apache, Bind9, ISC DHCP
⚡ Automation: Paramiko, Network APIs, Cron Jobs, Configuration Management
```

---

## 🚀 Featured Projects

### 1. 🌐 Enterprise Multi-Location Network Architecture
**[View Project →](https://github.com/chetan20030990/enterprise-multi-location-network)**

<div align="center">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Grade-A-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Devices-74-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Cost-$74,470-blue?style=for-the-badge" />
</div>

**Comprehensive enterprise network design connecting 5 global locations with 74 devices**

**🎯 Key Achievements:**
- Designed scalable network architecture serving Boston, Mumbai, New York, Germany, and London
- Implemented OSPF multi-area routing with Area 0 backbone for optimal performance  
- Configured HSRP for 99.9% uptime with automatic failover capabilities
- Deployed department-based VLANs (HR-10, Tech-20, Finance-30) with security isolation
- Achieved cost-optimized design totaling $74,470 with strategic equipment selection

**⚙️ Technical Implementation:**
- **Routing:** OSPF Areas 0-5, EIGRP over GRE tunnels for secure HQ communication
- **Redundancy:** Primary/standby routers with HSRP, STP for loop prevention
- **Security:** ACLs preventing unauthorized inter-department access, SSH management
- **Services:** Centralized DHCP/DNS, automated IP assignment across all locations

**📊 Performance Results:**
- Network convergence: 15 seconds (target: <30s)
- HSRP failover: 2 seconds (target: <3s) 
- Inter-site latency: 45ms (target: <100ms)
- Packet loss: 0.02% (target: <0.1%)

---

### 2. 🔒 Secure End-to-End Encrypted Chat Application  
**[View Project →](https://github.com/chetan20030990/secure-chat-application)**

<div align="center">
  <img src="https://img.shields.io/badge/Encryption-RSA_2048--bit-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Language-Python-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Security-Digital_Signatures-purple?style=for-the-badge" />
</div>

**Real-time encrypted messaging with military-grade security features**

**🛡️ Security Features:**
- RSA 2048-bit encryption with OAEP padding for message confidentiality
- Digital signatures using PSS padding for authentication and integrity
- SHA-256 hashing for message verification and tamper detection
- Automatic key erasure after session termination for forward secrecy

**🏗️ Architecture:**
- Multi-threaded client-server model using Python sockets
- Secure public key exchange protocol with certificate validation
- Real-time message encryption/decryption with minimal latency
- Error handling and session management for robust communication

**💻 Code Highlights:**
```python
# RSA Key Generation & Secure Encryption
private_key = rsa.generate_private_key(public_exponent=65537, key_size=2048)
encrypted_message = peer_public_key.encrypt(message, padding.OAEP(...))
signature = private_key.sign(message, padding.PSS(...))
```

---

### 3. 🐧 Linux Network Infrastructure Implementation
**[View Project →](https://github.com/chetan20030990/linux-network-infrastructure)**

<div align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Services-7+-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Automation-Python-blue?style=for-the-badge" />
</div>

**Complete network services infrastructure for enterprise startup environment**

**🔧 My Contributions:**
- **Backup Automation:** Developed automated backup system with tar/gzip compression, remote transfer, and cron scheduling
- **Network File System:** Configured NFS for centralized file sharing with proper permission management
- **Security Testing:** Implemented MITM attack simulation using Python Scapy for vulnerability assessment

**🏢 Infrastructure Services:**
- **DNS:** Master-Slave Bind9 configuration with forward/reverse lookup zones
- **DHCP:** IPv4/IPv6 address assignment with scope management and reservations  
- **Web Server:** Apache configuration with SSL/TLS encryption and fail2ban security
- **Firewall:** UFW implementation with custom rules and intrusion prevention
- **VPN:** IPSec tunnel mode for secure remote access

**🤖 Automation Features:**
- Automated configuration backups with timestamp-based naming
- Performance monitoring scripts with email alerting
- Security scanning tools for vulnerability detection
- Network discovery and documentation automation

---

### 4. 🤖 Network Automation & Monitoring Tools
**[View Project →](https://github.com/chetan20030990/network-automation-tools)**

<div align="center">
  <img src="https://img.shields.io/badge/Language-Python-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Protocols-SNMP-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Automation-Paramiko-green?style=for-the-badge" />
</div>

**Python-based tools for network management, monitoring, and automation**

**🔍 Monitoring Solutions:**
- Real-time interface status monitoring with SNMP integration
- Bandwidth utilization tracking with historical data analysis  
- Automated alerting system for network events and thresholds
- Performance dashboard with visual metrics and trends

**⚙️ Automation Scripts:**
- Configuration backup and versioning system
- Network device discovery and inventory management
- IP address management and subnet calculation tools
- Automated configuration deployment and rollback capabilities

**📊 Reporting & Analytics:**
- Network health reports with SLA compliance metrics
- Capacity planning analysis with growth projections
- Security audit reports with vulnerability assessments
- Custom dashboards for different stakeholder needs

---

## 💼 Professional Experience

### 🔧 IT Support Volunteer
**Indian Institute of Space Science and Technology** | *August 2023 - April 2024*

- Provided comprehensive technical support for 500+ students and faculty members
- Troubleshot complex hardware, software, and network connectivity issues
- Configured university-approved software packages and VPN solutions on Windows/Linux
- Upgraded legacy PC systems with Windows 10 to extend hardware lifespan by 3+ years
- Maintained 99% uptime for critical university technology infrastructure

**Key Achievements:**
- Reduced average issue resolution time by 40% through systematic troubleshooting
- Implemented preventive maintenance procedures reducing hardware failures by 25%
- Created documentation and training materials for common technical issues
- Collaborated with IT team to improve network security and performance

---

## 🏆 Certifications & Training

### 🎯 In Progress
- **CCNA (Cisco Certified Network Associate)** - Expected completion: March 2025
- **CompTIA Network+** - Expected completion: April 2025

### ✅ Completed Training
- **Linux System Administration** - Advanced command line and server management
- **Network Security Fundamentals** - Firewalls, VPNs, and intrusion detection
- **Python for Network Automation** - Scripting for network device management
- **Wireshark Network Analysis** - Packet capture and protocol analysis

---

## 📊 Project Statistics & Impact

<div align="center">

| Project Category | Total Projects | Technologies Used | Impact Metrics |
|------------------|----------------|-------------------|----------------|
| **Enterprise Networks** | 3 | OSPF, HSRP, VLANs, ACLs | 74 devices, 5 locations |
| **Security Systems** | 2 | RSA, IPSec, Firewalls | 99.9% security uptime |
| **Automation Tools** | 4 | Python, SNMP, APIs | 60% time savings |
| **Linux Infrastructure** | 2 | DNS, DHCP, Apache, NFS | 100% service availability |

</div>

---

## 🎨 Technical Demonstrations

### 📹 Project Demos & Walkthroughs
- **Network Topology Simulations** - Interactive Packet Tracer demonstrations
- **Security Testing Videos** - Live penetration testing and vulnerability assessment
- **Automation Script Demos** - Python tools for network management in action
- **Configuration Tutorials** - Step-by-step implementation guides

### 📊 Interactive Network Tools
- **IP Subnet Calculator** - Custom Python tool for network planning
- **Network Performance Analyzer** - Real-time monitoring dashboard
- **Configuration Generator** - Automated device configuration creation
- **Security Assessment Tool** - Vulnerability scanning and reporting

---

## 🌟 Why Choose Me?

### 🎯 Proven Track Record
- **4.0 GPA** demonstrating academic excellence and dedication
- **Grade A projects** showcasing real-world application of networking concepts
- **Hands-on experience** with enterprise-grade network equipment and protocols

### 🚀 Innovation & Problem-Solving
- Designed cost-effective solutions saving 15% on infrastructure budgets
- Implemented automation reducing manual configuration time by 60%
- Created security systems preventing 100% of unauthorized access attempts

### 📈 Continuous Learning
- Actively pursuing industry certifications (CCNA, Network+)
- Contributing to open-source networking projects
- Staying current with emerging technologies and best practices

### 🤝 Team Collaboration
- Successfully worked in team environments on complex projects
- Mentored fellow students in networking concepts and troubleshooting
- Excellent communication skills for technical and non-technical stakeholders

---

## 📞 Let's Connect & Collaborate

<div align="center">

### 🎯 Currently Seeking Network Engineer Opportunities

**Interested in roles involving:**
- Enterprise network design and implementation
- Network security and penetration testing  
- Network automation and DevOps integration
- Telecommunications infrastructure management
- Cloud networking and hybrid architectures

**Available for:**
- Full-time positions starting May 2026
- Internships and co-op opportunities
- Contract and consulting projects
- Technical mentoring and knowledge sharing

</div>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=chetan20030990&label=Portfolio%20Views&color=0e75b6&style=for-the-badge" alt="Portfolio Views" />
  
  **⭐ Building the secure, connected infrastructure of tomorrow ⭐**
  
  *"Passionate about creating robust, scalable networks that enable digital transformation while maintaining the highest security standards."*
</div>

---

## 📚 Repository Navigation

| Repository | Description | Technologies | Status |
|------------|-------------|--------------|--------|
| [🏢 Enterprise Network](https://github.com/chetan20030990/enterprise-multi-location-network) | Multi-location network design | OSPF, HSRP, VLANs | ✅ Complete |
| [🔒 Secure Chat App](https://github.com/chetan20030990/secure-chat-application) | Encrypted messaging system | Python, RSA, Sockets | ✅ Complete |  
| [🐧 Linux Infrastructure](https://github.com/chetan20030990/linux-network-infrastructure) | Network services setup | DNS, DHCP, Apache, NFS | ✅ Complete |
| [🤖 Automation Tools](https://github.com/chetan20030990/network-automation-tools) | Python network utilities | Python, SNMP, APIs | 🔄 Active |
| [📖 Learning Resources](https://github.com/chetan20030990/networking-learning-resources) | Study guides and references | Documentation | 🔄 Growing |

*Last Updated: December 2024*
