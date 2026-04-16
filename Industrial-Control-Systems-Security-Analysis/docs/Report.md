# Industrial Control Systems Security Audit: Gap Analysis and Risk Mitigation for Väst Vindpark 

 

Date: 2026-04-16 

Author: Baiar Yusuf


## Executive Summary 

This report checks the cybersecurity of Väst Vindpark AB’s IT and OT networks. I found big security problems. For example, we do not watch the OT network traffic, and the firewalls are completely open. This makes it easy for hackers to move around in the system. 

These problems make it easy for unauthorized people to access the wind turbines, which is dangerous. I recommend fixing the 5 main problems listed in this report. This will make the system safe and follow security standards.

## 1 Asset Inventory & Network Architecture 

### 1.1 Asset Inventory Overview  

The asset list shows the computers and network parts at Väst Vindpark AB. We organize them using the Purdue model and Security Levels (SL). A good list helps us understand our risks.

Right now, our asset list is not finished. We are missing important details like operating systems and model numbers. Because of this, it is harder to do a perfect security check.

Väst Vindpark has two wind turbines. The OT network controls and monitors the turbines. The IT network handles business tasks and allows remote workers to connect via VPN.

### 1.2 Logical Network Drawing & Zoning (Purdue Model)
<img width="1376" height="1697" alt="bild (1)" src="https://github.com/user-attachments/assets/f55caadc-f0fc-4c60-9aeb-8c80f76af61b" />

### 1.3 Security Levels and Conduits  

### System Overview
For a complete list of hardware and software components, see the
[Asset Inventory](https://github.com/ITS25-OT/Industrial-Control-Systems-Security-Analysis/blob/main/assets/asset-inventory.md)

## 2 Risk Assessment Insights 

### 2.1 Executive Summary of Risk Findings  

The biggest risks for Väst Vindpark are poor network separation, weak passwords, and no network monitoring. Because the firewalls are open and passwords are weak, attackers can easily steal data or take control of the wind turbines.

### 2.2 High-level Risk Insights  

* **Open Networks:** The firewalls between IT, IDMZ, and OT do not block anything. This gives hackers a direct path to our critical systems.
* **Weak Logins (IAM):** Users share accounts and have simple passwords. We do not use Multi-Factor Authentication (MFA). It is easy for someone to steal an account.
* **No Visibility:** We do not have a system (like an IDS) to watch for hackers in the network.
* **Missing Logs:** Security logs are not collected in one central place. If we get attacked, it is hard to find out what happened.
* **Software Updates:** We do not have a good routine for updating systems, which leaves "open doors" for attackers.

### 2.3 Risk Appetite and Tolerance Levels 

Väst Vindpark is very important for society (NIS2 rules). Therefore, we cannot accept risks that stop the turbines or put people in danger. We must fix high risks immediately to keep the operations running safely.

### 2.4 Residual Risk and Compensating Controls 

We can accept a little more risk in SL 1 and 2, but zones in SL 3 and 4 must be very safe. Sometimes, basic rules are not enough. For example, just having a password is not safe enough for critical systems. We must add Multi-Factor Authentication (MFA) to lower the risk to a safe level.

### Security Analysis
The potential threats and vulnerabilities for the system have been evaluated in the
[Risk Assessment](https://github.com/ITS25-OT/Industrial-Control-Systems-Security-Analysis/blob/main/docs/Risk_assessment.md)

## 3 Gap Analysis & High-level Roadmap

### 3.1 Key Highlights from Gap Analysis 
The Gap Analysis shows that we are missing basic security. Anyone can pass through our firewalls. We do not have MFA, and we do not monitor our network for attacks. We need to focus on the 5 most important steps to make the system safe again.

### 3.2 Prioritized Gap Insights 
I have prioritized the top 5 security actions from IEC 62443-3-3. This plan will help lower the risks.

**Phase One (0-3 months)**
1. **SR 2.1 Authorization enforcement:** Use Role-Based Access so people only get the access they need for their job.
2. **SR 1.1 Human User Identification and Authentication:** Turn on MFA to protect all accounts.
3. **SR 5.1 Network segmentation:** Fix the firewalls to block all bad traffic between IT and OT.

**Phase Two (3-6 months)**
4. **SR 6.1 Audit log accessibility:** Save all security logs in a central server so we can investigate problems easily.
5. **SR 6.2 Continuous monitoring:** Install a tool (IDS) to watch the network traffic for strange activity.

### 3.3 High-level Implementation Roadmap

### Compliance and Improvements
To identify the differences between current security measures and the desired security state, refer to the
[Gap Analysis](https://github.com/ITS25-OT/Industrial-Control-Systems-Security-Analysis/blob/main/docs/Gap-Analysis.md)