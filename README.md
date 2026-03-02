# IAM Labs Portfolio — Monese Williams

## 👋 About Me
I am an Information Technology student and aspiring Identity & Access Management (IAM) professional.  
This repository documents **hands-on IAM labs** completed using **Microsoft Entra ID (Azure AD)**, focused on real-world enterprise identity and access scenarios.

My approach emphasizes:
- Least Privilege
- Zero Trust
- Group-based access control
- Governance and lifecycle management

I take time to understand *why* access is granted, not just *how*.

---

## 🔐 IAM Labs Overview

### 🧪 Lab 1 — User & Group Management
**Objective:** Establish identity foundations  
- Created user accounts in Microsoft Entra ID  
- Created security groups for organized access management  
- Assigned users to groups instead of individual permissions  
- Applied least privilege principles  

---

### 🧪 Lab 2 — Authorization (RBAC & Roles)
**Objective:** Control access safely and realistically  
- Created admin security groups  
- Assigned directory roles using group-based role assignment  
- Removed direct user role assignments  
- Reduced over-privileged access  
- Verified role assignments after changes  

---

### 🧪 Lab 3 — Conditional Access & MFA
**Objective:** Protect privileged accounts  
- Created Conditional Access policies  
- Enforced MFA for admin roles  
- Applied policies in Report-Only mode to validate impact  
- Verified access enforcement through role and group membership  

---

### 🧪 Lab 4 — Governance & Auditing
**Objective:** Ensure access remains appropriate over time  
- Performed access reviews  
- Verified role assignments after changes  
- Audited admin access instead of assuming security  
- Applied Zero Trust principles (“never trust, always verify”)  

---

### 🧪 Lab 5 — Joiner–Mover–Leaver Lifecycle
**Objective:** Simulate real IAM operations  
- Onboarded a new user with no default access  
- Assigned access through admin groups (not individually)  
- Verified MFA enforcement via Conditional Access  
- Removed access when role was no longer required  
- Deprovisioned user account upon termination  
- Verified access removal and account deletion  

---

## 🛠 Tools & Technologies
- Microsoft Entra ID (Azure Active Directory)
- Conditional Access
- RBAC (Role-Based Access Control)
- MFA
- IAM Governance
- Zero Trust Security Model

---

## 📌 Notes
These labs reflect how IAM work is performed in real environments —  
**access is verified, reviewed, and governed**, not assumed.

---


