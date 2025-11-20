
# SignalAge Incident Response Plan (2025 Edition)

A practical, SMB-ready incident response framework aligned with **NIST 800-61 Rev.2** and optimized for cloud-first environments.

---

## 1. Objectives
- Minimize operational disruption  
- Contain and eradicate threats quickly  
- Preserve forensic evidence  
- Restore systems with minimal downtime  
- Improve resilience through continuous feedback  

---

## 2. Roles & Responsibilities (RACI)

| Role | Responsibility | Contact |
|------|----------------|---------|
| **Incident Response Lead (IRL)** | Overall coordination | info@signalage.com |
| **Technical Response Team (TRT)** | Forensics, containment, remediation | info@signalage.com |
| **Communications Lead** | Internal + external communication | info@signalage.com |
| **Legal / Compliance** | Regulatory guidance | info@signalage.com |

---

## 3. Incident Severity Levels

| Level | Description | Example |
|-------|-------------|---------|
| **Critical** | Major business disruption | Ransomware |
| **High** | Sensitive access or lateral movement | Account compromise |
| **Medium** | Limited but suspicious activity | Malware detection |
| **Low** | No confirmed impact | Failed login spikes |

---

## 4. IR Lifecycle (NIST Aligned)

### **4.1 Preparation**
- MFA enforced everywhere  
- Offline & encrypted backups  
- CIS v8 Level 1 controls baseline  
- Updated asset inventory  
- Logging enabled for cloud, endpoint, identity  

---

### **4.2 Detection & Analysis**
**Common IOCs**
- Impossible travel  
- Suspicious admin activity  
- Unexpected mailbox rules  
- Abnormal outbound traffic  
- High-volume encryption events  

**Recommended Tools**
- Microsoft Defender  
- Rapid7 InsightIDR  
- CloudTrail / Sentinel  
- Sysmon  

---

### **4.3 Containment**
**Short-Term**
- Disable compromised users  
- Block malicious IPs  
- Isolate infected endpoints  

**Long-Term**
- Reset affected credentials  
- Patch vulnerable assets  
- Enforce stronger conditional access policies  

---

### **4.4 Eradication**
- Remove malware & persistence  
- Revoke OAuth permissions  
- Rotate secrets & API keys  
- Remove rogue cloud assets  

---

### **4.5 Recovery**
- Restore validated backups  
- Stage-by-stage reconnection  
- Validate integrity (checksum verification)  
- Monitor for recurrence 72 hours  

---

### **4.6 Lessons Learned**
Within 7 days:
- Root Cause Analysis (RCA)  
- Timeline reconstruction  
- Control gap mapping  
- Update policy/documentation  

---

## 5. Playbooks

### **Ransomware**
1. Isolate devices  
2. Stop file-sharing  
3. Preserve encrypted samples  
4. Identify strain  
5. Restore from clean backups  
6. Notify affected parties if required  

### **Phishing / BEC**
1. Quarantine message  
2. Reset credentials  
3. Review mailbox rules  
4. Check OAuth apps  
5. Alert finance  
6. Assess lateral movement  

### **Cloud Breach**
1. Review audit logs  
2. Terminate suspicious sessions  
3. Rotate keys  
4. Review IAM access  
5. Apply restrictive policies  

---

## 6. KPIs
- MTTD  
- MTTR  
- MFA adoption rate  
- % of critical assets monitored  
- Recurrence rate  

---

## 7. Document Owner
Maintained by **SignalAge Security Team**  
Last Updated: 2025
