# **Cybersecurity Research Report: The Shift to AI-Driven Attacks and Defense**

**Date:** April 16, 2026  
**Topic:** New Tech and Major Recent Attacks (2025-2026)

---

## **Summary**
Cybersecurity has changed a lot between late 2025 and early 2026. We have moved from people slowly fighting each other to AI programs fighting at machine speed. New AI models like Claude Mythos and tools like Novee can find and use security holes in hours instead of weeks. At the same time, recent hacks like the ones on Jaguar Land Rover and Stryker show that hackers are now trying to destroy systems or stop production entirely rather than just stealing data.

---

## **Section 1: New Tech for Red and Blue Teams**

### **AI for Attacking (Red Teaming)**
The biggest change in offensive security is the use of Autonomous Red Agents. These are AI tools that can think for themselves to find ways into a network.

*   **Novee and Vulnerability Chaining:** Novee is a new tool that does more than just scan for bugs. It uses a specialized engine to chain small mistakes together. For example, it might find a tiny setting error and then use it to take over a whole system through a developer tool like Cursor. This shows how AI can find complex paths that a human might miss.
*   **Claude Mythos (Project Glasswing):** This is a powerful AI model from Anthropic that allegedly has an 83.1% success rate at finding zero-day bugs. However, because this model is currently restricted to a private group of companies, it is hard to tell if these numbers are completely accurate. Until the model is more widely used and tested by independent researchers, there is a possibility that these claims are partly for publicity or to help with sales.
*   **Interactive Deepfakes:** Hackers are now using AI to make deepfake video and audio during live calls. They can copy a boss's voice and even make the video look like they are blinking and moving naturally. This makes it almost impossible for employees to tell if a call is fake. A major example of this was the $25 million Arup fraud case in early 2026.

### **AI for Defending (Blue Teaming)**
Defenders are fighting back with their own AI tools to keep up with the speed of attacks.

*   **Predictive Defense:** New platforms like SentinelOne use AI to guess which bugs hackers will use next. Instead of trying to fix everything, they focus on the bugs that are actually reachable by an attacker. This helps security teams use their time much more effectively.
*   **CTEM and Sigma Rules:** Companies are moving to a framework called Continuous Threat Exposure Management (CTEM). Instead of checking security once a year, they do it every day. When an AI tool finds a new attack path, it automatically writes a Sigma rule. This is a standard piece of code that helps the security team catch that specific attack immediately.
*   **AI Auto-Fixing:** Some tools can now write the code to fix a bug as soon as it is found. This helps companies patch their systems much faster, which is necessary when attackers are using AI to find those same bugs.

---

## **Section 2: Impactful Recent Incidents**

### **Case Study 1: Jaguar Land Rover (JLR) Ransomware (Late 2025)**
**Attacker:** A group called Scattered Lapsus$ Hunters.  
**How it Happened:** They used voice phishing to trick people in charge of the company databases and also used stolen Jira passwords. Once they were in, they moved through the network using a VPN and hid their tracks using the TOR network.  
**Result:** JLR had to stop making cars for 5 weeks in the UK, Slovakia, and Brazil. This cost the economy about £1.9 billion.  
**Prevention:** To prevent this in the future, companies should use Zero Trust architecture and physical security keys for logins.

### **Case Study 2: Stryker MedTech Wiper Attack (March 2026)**
**Attacker:** A group called Handala.  
**How it Happened:** This was a very dangerous wiper attack because the hackers did not even use a virus. Instead, they stole the admin password for Microsoft Intune, which is the tool the company uses to manage all its laptops. They just sent a Remote Wipe command to every single device.  
**Result:** This caused 200,000 laptops and servers to be wiped clean in 79 different countries.  
**Why it Succeeded:** Because the wipe command was a legal tool, the antivirus software did not try to stop it.  
**Prevention:** Administrators should only have wipe powers for a few minutes when they actually need them.

---

## **Section 3: Sources and Bias Check**

To make sure this report is accurate, I checked many different sources like CISA, Mandiant, and major news sites.

*   **Checking for Conflicts:** At first, some people thought the Stryker attack used a new virus called DynoWiper. But later, experts found out it was actually just the hackers using the Microsoft Intune tool. I used the updated information for this report because it matches the technical facts.
*   **Checking for Bias:** Many companies that sell security tools claim their AI can stop every attack. I tried to ignore the sales pitch and only looked at what actually happened in real attacks. I also acknowledged that the Claude Mythos data comes from Anthropic itself. This could be a conflict of interest, so we should stay skeptical until the model is more widely used.

---

## **Necessary Steps for 2026**
1.  **Use continuous testing (CTEM)** instead of less frequent checks.
2.  **Use hardware security keys** for all important accounts.
3.  **Monitor for bulk actions** in management tools like Intune to stop mass wipes.
4.  **Use tools** and utmost caution to verify if video calls are real or deepfakes.

---

## **Sources**
*   CISA (Cybersecurity and Infrastructure Security Agency) Reports 2025-2026.
*   Mandiant / Google Cloud M-Trends 2026 Report.
*   CrowdStrike Global Threat Report 2026.
*   Anthropic Project Glasswing Safety Disclosures.
*   Palo Alto Networks (Unit 42) Incident Analysis of Stryker Breach.
*   Gartner Strategic Technology Trends for 2026 (CTEM and AI-TRiSM).
*   AI Security Institute (AISI) Frontier Model Evaluations.
*   News coverage from TechCrunch, The Cyber Express, and LevelBlue.
