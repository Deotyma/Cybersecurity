# Security audit of Botium Toys company

## **Controls Assessment Checklist**
| Control | Implemented? |
|-------------------------------|--------------|
| **Least Privilege** | ❌ No |
| **Disaster Recovery Plans** | ❌ No |
| **Password Policies** | ✅ Yes (but weak) |
| **Separation of Duties** | ❌ No |
| **Firewall** | ✅ Yes |
| **Intrusion Detection System (IDS)** | ❌ No |
| **Backups** | ❌ No |
| **Antivirus Software** | ✅ Yes |
| **Manual Monitoring & Maintenance for Legacy Systems** | ✅ Yes (but irregular) |
| **Encryption** | ❌ No |
| **Password Management System** | ❌ No |
| **Locks (Offices, Storefront, Warehouse)** | ✅ Yes |
| **Closed-Circuit Television (CCTV) Surveillance** | ✅ Yes |
| **Fire Detection/Prevention (Fire Alarm, Sprinkler)** | ✅ Yes |

---

## **Compliance Checklist**
### **Payment Card Industry Data Security Standard (PCI DSS)**
| Best Practice | Compliant? |
|-----------------------------------------------------|--------------|
| Only authorized users have access to customers’ credit card information. | ❌ No |
| Credit card information is stored, accepted, processed, and transmitted securely. | ❌ No |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data. | ❌ No |
| Adopt secure password management policies. | ❌ No |

### **General Data Protection Regulation (GDPR)**
| Best Practice | Compliant? |
|-------------------------------------------------|--------------|
| E.U. customers’ data is kept private/secured. | ❌ No |
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | ✅ Yes |
| Ensure data is properly classified and inventoried. | ❌ No |
| Enforce privacy policies, procedures, and processes to properly document and maintain data. | ✅ Yes |

### **System and Organizations Controls (SOC Type 1, SOC Type 2)**
| Best Practice | Compliant? |
|-------------------------------------------|--------------|
| User access policies are established. | ❌ No |
| Sensitive data (PII/SPII) is confidential/private. | ❌ No |
| Data integrity ensures the data is consistent, complete, accurate, and has been validated. | ✅ Yes |
| Data is available to individuals authorized to access it. | ✅ Yes |

---

## **Recommendations for IT Manager**
1. **Prioritize access control**: Implement least privilege and separation of duties to restrict access to sensitive data.
2. **Enhance compliance with PCI DSS**:
   - Encrypt stored and transmitted credit card information.
   - Limit access to customer payment data only to authorized personnel.
   - Adopt a secure password management system.
3. **Implement a disaster recovery and backup plan** to ensure business continuity in case of data loss.
4. **Deploy an Intrusion Detection System (IDS)** to monitor network traffic and detect unauthorized access attempts.
5. **Strengthen password policies** by enforcing strong complexity requirements and integrating a centralized password management system.
6. **Improve GDPR compliance**:
   - Implement stricter access controls for E.U. customers' personal data.
   - Classify and inventory data to ensure proper management.
7. **Schedule regular monitoring and maintenance** for legacy systems to mitigate potential vulnerabilities.

This assessment highlights critical security gaps that need immediate attention. Strengthening compliance and implementing missing controls will significantly improve Botium Toys’ security posture.
