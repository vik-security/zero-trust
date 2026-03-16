# Zero Trust
Zero Trust is a foundational principle that treats security as a baseline requirement. While no single approach can eliminate cyber threats entirely, implementing a Zero Trust architecture, together with other security principles and controls, contributes to significant risk reduction.

NIST Special Publication 800-27 states:

> "Zero trust (ZT) is the term for an evolving set of cybersecurity paradigms that move defenses from static, network-based perimeters to focus on users, assets, and resources. A zero trust architecture (ZTA) uses zero trust principles to plan industrial and enterprise infrastructure and workflows. Zero trust assumes there is no implicit trust granted to assets or user accounts based solely on their physical or network location or asset ownership. Authentication and authorization (both subject and device) are discrete functions performed before a session to an enterprise resource is established. Zero trust is a response to enterprise network trends including remote users, BYOD, and cloud-based assets that are not located within an enterprise-owned network boundary. Zero trust focuses on protecting resources (assets, services, workflows, network accounts, etc.), not network segments, as the network location is no longer the primary component of a resource's security posture."


In simpler terms, ZT architecture treats all incoming connections, systems, users and devices as unknown and unverified by default. Only those that are explicitly validated and match system records are granted access. All others are denied. 

---
# Real-world application

As an example, imagine you own a building with offices, storage rooms and common areas. Unlike a traditional building where an employee badge gets you through the front entrance and then lets you wander around. In ZT building, every door requires you to verify who you are and why you need access in addition to you already getting passed the initial entrance. While common areas will let users roam around, rooms with doors and locks will check your identity, role and whether you should be there, every single time.  

---

## Baseline Practices for Zero-Trust Architecture

These are key controls to prevent unauthorized system access:


- Block legacy authentication; use only modern authentication standards (OAuth2, OpenID, SAML)  
- Enable geo-blocking  
- Enforce multi-factor authentication (MFA) for all accounts  
- Apply conditional access policies based on user role, device compliance, and location  
- Monitor and detect suspicious login behavior  
- Enforce least privilege access for all accounts  
- Encrypt data both in transit and at rest  
- Implement Role-Based Access Control (RBAC) for all internal systems  
- Deploy Data Loss Prevention (DLP) tools  
- Apply patch management across all systems  
- Change default account logins and passwords  
- Enforce strong anti-spam email policies  
- Design robust firewall policies for publicly-facing assets  
- Conduct security awareness training and phishing simulations  
- Apply strong identity and access management for applications  
- Enforce Mobile Device Management (MDM) security policies  
- Deploy EDR/XDR solutions to all physical and cloud endpoints
