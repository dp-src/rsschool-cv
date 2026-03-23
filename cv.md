# Darya Panova
### Contact information
**Location:** Temirtau, Kazakhstan  
**Phone:** +7 (707) 815-61-10  
**E-mail:** panovadv24@gmail.com  
**Telegram:** @dp_src  
**GitHub:** [@dp_src](https://github.com/dp-src)  

---
### About Me  
Taking a Frontend course to master JavaScript fundamentals and the principles of web services. I am not focused on design or visual styling. My interests lie in data processing logic, algorithms, and working with data structures. My goal is to gain the technical skills to manually implement projects that I currently prototype using AI. My long-term goal is to transition into Backend development and database management, where I can apply a structured and systematic approach.

---
### Skills
* **Hard Skills:** * Programming Foundations (Logic, Loops, Data Types)
    * Version Control (Git, GitHub)
    * Documentation & Markup (Markdown)
    * Basic Python (Algorithm implementation)
    * System Logic Design (Flowcharts, hardware-software interaction mapping)
* **Soft Skills:**
    * **Analytical Mindset:** Ability to decompose complex systems and identify logical vulnerabilities.
    * **Self-Learner:** Proven ability to master new tools (AI, complex hardware APIs) independently.
    * **Critical Thinking:** A skeptical approach to ready-made solutions, aiming to understand the underlying mechanics.
    * **Systems Thinking:** Focusing on how individual components integrate into a larger architecture.  

---
### Education
* **Rolling Scopes School**
  * JS / Front-end Pre-school (2026Q1)
* **Python Generation: Course for Beginners (Stepik)**
  * [Certificate #2104885](https://stepik.org/cert/2104885?lang=en)  
  
---
### Experience
*NOTE: AI projects were developed through AI-Agent Orchestration. I defined system behavior, steering the AI agent through iterative requirements, and performing rigorous functional validation. I managed the development cycle without writing or reading code, focusing instead on business logic, edge-case discovery, and final product integrity.*

#### Seal Ring Selection Calculator
*A customer-facing web utility for product discovery and price estimation.*

- **Inclusive Search Logic:** Conceptualized a "dual-criteria" matching algorithm. It allows users to find products by either Physical Dimensions or GOST Standards, ensuring a match is found even if specifications differ from physical measurements.
- **Commercial Logic:** Defined the rules for dynamic price estimation based on quantity-based volume ranges within the search results.
- **Lead Generation Flow:** Designed the end-to-end user journey where selected items are compiled into a formal request and automatically dispatched to a sales manager's email for final manual verification and technical consulting.
- **UX Guardrails:** Enforced "foolproof" validation rules to guide users through complex technical parameters, ensuring the AI-generated interface prevents invalid search queries.

#### Access Control System Prototype

*A standalone Access Control System for real-time visitor and staff monitoring (designed for large-scale facilities with 600+ capacity).*

- **Real-time Flow Monitoring:** Engineered a system to monitor facility occupancy by centralizing data from diverse hardware: Dahua turnstiles for guests and Hikvision face-recognition terminals for staff.
- **Data Discovery & Protocol Extraction:** Used Wireshark and Browser DevTools to capture raw network traffic and API requests from devices. Directed the AI to decode these proprietary structures to enable hardware-to-server communication without official documentation.
- **Complex Shift Logic:** Conceptualized and enforced a time-tracking algorithm for overnight shifts (crossing midnight). The system correctly merges entry/exit events into a single session even when they occur on different calendar days.
- **Scalability & Performance:** Engineered the logic to handle 600+ visitors via only 3 turnstiles, ensuring the database (SQLite WAL) remains stable even with 5M+ log records.
- **Telegram Integration:** Orchestrated a bot for remote management, device status monitoring, and instant statistics. Implemented automated delivery of styled Excel reports (.xlsx) with custom color-coding directly to the Telegram chat.
- **Autonomy & Self-Healing:** The system is fully local (operates without internet), featuring automated database recovery, disk-space protection (log rotation), and a hardware-bound licensing prototype (QR-code based).

---
### Code Examples
**[Calculate average](https://www.codewars.com/kata/57a2013acf1fa5bfc4000921) task from Codewars:**  
*Write a function which calculates the average of the numbers in a given array.  
Note: Empty arrays should return 0.*

```
function findAverage(array) {
  let sum = 0;
  if (array.length === 0) {
    return 0;
  } else {
    for (let i = 0; i < array.length; i++) {
      sum += array[i];
    }
    return (sum / array.length);
  }
}
```

---
### Languages
* **Russian:** Native
* **English:** C1 Advanced (accordind to [EF SET](https://cert.efset.org/en/Lkf1v8) test)
* **Kazakh:** A2 Waystage