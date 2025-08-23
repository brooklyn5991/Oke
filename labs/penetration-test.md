
# 🧪 Lab: Penetration Testing Stages

## 📌 Overview
- **Platform:** TryHackMe  
- **Difficulty:** Beginner  
- **Goal:** Understand the stages of a penetration test and their importance.  

---

## 🔍 Stages of a Penetration Test

### 1. Rules of Engagement
- Legal agreement signed between client and tester.  
- Defines **scope** (e.g., only a specific app, not full network).  
- Defines **rules** (what is allowed vs. not allowed).  

---

### 2. Information Gathering
- Collect intel from public sources (OSINT).  
- Example: Employee shares email & job role on LinkedIn → attackers could:  
  - Attempt phishing  
  - Use email as a valid username for brute force  
  - Map company structure  

**Defenses:**  
- Train employees on safe social media use.  
- Don’t share work emails in bios.  
- Use phishing-resistant MFA & email filtering.  

---

### 3. Enumeration & Scanning
- Build a complete picture of the target:  
  - User accounts  
  - Applications & services  
  - Network shares  
  - Machines on the network  

---

### 4. Exploitation
- Actively attempt to exploit discovered vulnerabilities.  

---

### 5. Post-Exploitation
- Maintain access.  
- Escalate privileges.  
- Pivot to other systems in the network.  

---

### 6. Reporting
- Deliver a report to the client including:  
  - Findings  
  - Impacts  
  - Recommendations  

---

## 📚 Key Learnings
- Rules of engagement keep pentesting **legal & ethical**.  
- OSINT can reveal **critical attack paths**.  
- Enumeration is the foundation for exploitation.  
- A pentest is not complete without **clear reporting**.  
