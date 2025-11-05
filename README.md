# Self-Study MUST Be Free: Cybersecurity Library

A curated shelf of cybersecurity, hacking, and supporting fundamentals collected so that anyone can self-study without a paywall. The books live in the repository root; this guide explains how they fit together and how to chart your own path.

### Google Drive Link: https://drive.google.com/drive/folders/1eocSz3hnalhkdJ_LfNKuXWADwRp_M23L?usp=sharing

## How to Use This Library

- Start with the **Supporting / Prerequisite** titles if you are brand new to programming, operating systems, or networking.
- Within every domain, books are ordered **beginner -> intermediate -> advanced** so you can ramp up smoothly.
- Notes stay tightly coupled to each title; there are no hidden assumptions or external prerequisites beyond what is stated.
- Mix and match based on your goals, but resist the urge to skip foundations; they unlock every advanced topic here.
- If you notice an essential title missing, open an issue or PR so the community can keep this list living.

## Table of Contents

0. [Supporting / Prerequisite Resources](#supporting--prerequisite-resources)
1. [Foundations / General Cybersecurity & Mindset](#1-foundations--general-cybersecurity--mindset)
2. [Penetration Testing / Red Team Methodology](#2-penetration-testing--red-team-methodology)
3. [Web Application Security & Bug Bounties](#3-web-application-security--bug-bounties)
4. [Network Security & Monitoring](#4-network-security--monitoring)
5. [Exploit Development & Binary / Memory Vulnerabilities](#5-exploit-development--binary--memory-vulnerabilities)
6. [Reverse Engineering & Malware Analysis](#6-reverse-engineering--malware-analysis)
7. [Mobile Application Security](#7-mobile-application-security)
8. [Cryptography](#8-cryptography)
9. [Defensive Security / Incident Response](#9-defensive-security--incident-response)
10. [Programming & Secure Coding](#10-programming--secure-coding)
11. [Scripting, Tooling & Automation](#11-scripting-tooling--automation)
12. [Browser & Client-Side Security](#12-browser--client-side-security)
13. [Social Engineering & Human Factors](#13-social-engineering--human-factors)
14. [Specialized / Miscellaneous Extras](#14-specialized--miscellaneous-extras)
15. [Suggested Learning Path](#15-suggested-learning-path)
16. [Quick Tips](#quick-tips)
17. [Contributing](#contributing)

---

## Supporting / Prerequisite Resources

- **Programming Fundamentals**
  - **Python Crash Course** by Eric Matthes — approachable way to build the scripting base you will reuse everywhere.
  - **Python Notes for Professionals** (GoalKicker) — quick-reference companion while practicing.
  - **The C Programming Language (2nd Edition)** by Kernighan & Ritchie — systems-level literacy for low-level security work.
  - **C++ for Hackers** by Steve Oualline — extends C foundations into modern C++ with a security mindset.
- **Operating Systems & Linux**
  - **Linux Basics for Hackers** by OccupyTheWeb — command-line, permissions, and toolchain essentials.
  - **Linux Command Line and Shell Scripting Bible** by Richard Blum & Christine Bresnahan — deeper shell automation and scripting coverage.
  - **Linux System Programming** by Robert Love — bridges user space and kernel interactions.
- **Networking Fundamentals**
  - **CCNA 200-301 Official Cert Guide** — structured walkthrough of networking core concepts.
  - **TCP/IP in C** by Michael J. Donahoo & Kenneth L. Calvert — applies networking theory through code.
- **Web Foundations**
  - **HTML & CSS: Design and Build Websites** by Jon Duckett — front-end basics that clarify web attack surfaces.
  - **HTML5 Canvas** by Steve Fulton & Jeff Fulton — interactive graphics surface insights for client-side exploits.

Tackle these first if any category feels unfamiliar; they shorten the time it takes to appreciate the security-focused titles that follow.

## 1. Foundations / General Cybersecurity & Mindset

- **The Cybersecurity Playbook** by Allison Cerra — program, process, and operational perspective for defenders.
- **The Basics of Hacking and Penetration Testing** by Patrick Engebretson — practical first steps into pentesting workflows.
- **CEH v10** by Ric Messier — certification-friendly breadth across core security domains.
- **Ethical Hacking: A Hands-on Introduction to Breaking In** by Daniel G. Graham — lab-driven entry point.
- **Ethical Hacking: Techniques, Tools, and Countermeasures** by Michael G. Solomon & Sean-Philip Oriyano — focuses on practical defense-aware techniques.

## 2. Penetration Testing / Red Team Methodology

- **The Hacker Playbook 3: Practical Guide to Penetration Testing** by Peter Kim — playbook approach to planning and executing attacks.
- **Hacking: The Art of Exploitation (2nd Edition)** by Jon Erickson — foundational exploitation concepts with C and assembly labs.
- **Advanced Penetration Testing** (Wiley) — red-team tradecraft and adversary simulation.
- **Metasploit: The Penetration Tester's Guide** by David Kennedy et al. — tool-driven exploitation workflows.
- **Coding for Penetration Testers** by Jason Andress & Ryan Linn — building custom tooling in support of engagements.

## 3. Web Application Security & Bug Bounties

- **Web Hacking 101** by Peter Yaworski — gentle intro to web vulns and bounty hunting.
- **The Web Application Hacker's Handbook** by Dafydd Stuttard & Marcus Pinto — deep-dive testing methodology.
- **WEB_HACKING** by Dafydd Stuttard & Marcus Pinto — companion reference covering additional scenarios.
- **OWASP Testing Guide v2 / v3 / v4** — community checklists and methodology for consistent assessments.
- **Real-World Bug Hunting** by Peter Yaworski — modern web bounty case studies.
- **XSS Sheet** by Rodolfo Assis — payload reference for client-side injection.
- **The Browser Hacker's Handbook** by Wade Alcorn et al. — browser internals and client-side exploitation.

### SQL / Database Attack Subset

- **All About SQL** — baseline SQL knowledge to understand relational targets.
- **Blind SQL Injection** by Kevin Spett — handling blind and time-based exploitation.
- **Advanced SQL Injection** by Justin Seitz — evasion and advanced payload strategies.

## 4. Network Security & Monitoring

- **CCNA 200-301 Official Cert Guide** — networking fundamentals to anchor later material.
- **The Practice of Network Security Monitoring** by Richard Bejtlich — detection, SOC operations, and network-centric defense.
- **TCP/IP in C** by Michael J. Donahoo & Kenneth L. Calvert — network programming with TCP/IP internals.
- **Sockets in C** by Panagiota Fatourou & Eleftherios Kosmas — socket patterns for tooling and exploit development.

## 5. Exploit Development & Binary / Memory Vulnerabilities

- **The Shellcoder's Handbook** by Chris Anley et al. — shellcode craft and vulnerability classes.
- **Buffer Overflow Exploitation** by Chester Rebeiro — practical overflow walk-throughs.
- **Linux Stack Based Buffer Overflow Exploitation** by Saif El-Sherei — Linux-specific exploitation flow.
- **Hacking: The Art of Exploitation** — revisit here for its low-level focus.
- **Linux Assembly** by Jeff Duntemann — assembly primer tailored to Linux environments.
- **The Art of High Level Assembly** by Randall Hyde — advanced assembly techniques.
- **OS Dev** by Nick Blundell & **Linux System Programming** by Robert Love — kernel and syscall background for advanced exploit work.

## 6. Reverse Engineering & Malware Analysis

- **Practical Malware Analysis** by Michael Sikorski & Andrew Honig — hands-on lab series for malware dissection.
- **Practical Malware Analysis (Hands-on Introduction)** — alternate print; same lab flow for redundancy.
- **Practical Reverse Engineering: x86, x64, ARM, Windows Kernel, Reversing Tools** by Bruce Dang et al. — architecture-spanning RE techniques.
- **The Art of Computer Virus Research and Defense** by Peter Szor — theoretical and historical grounding.
- **The Antivirus Hacker's Handbook** by Joxean Koret & Elias Bachaalany — antivirus internals and bypassing strategies.
- **The Android Malware Handbook** by Qian Han et al. — mobile-focused malware reverse engineering.

## 7. Mobile Application Security

- **Android Hacker's Handbook** by Joshua J. Drake et al. — platform internals and exploit paths.
- **The Mobile Application Hacker's Handbook** by Dominic Chell et al. — mobile assessment methodology.
- **Hacking Android** by Srinivasa Rao Koti — hands-on Android exploitation projects.
- **The Android Malware Handbook** — revisit for defensive/reverse engineering perspective.

## 8. Cryptography

- **Applied Cryptography** by Bruce Schneier — classic treatise blending theory and practice.
- **Cryptography in C and C++ (2nd Edition)** by Michael Welschenbach & David Kramer — implementation guidance bridging theory to code.

## 9. Defensive Security / Incident Response

- **The Practice of Network Security Monitoring** — repeat entry for defensive operations.
- **The Cybersecurity Playbook** — incident response planning and runbooks.
- Pair with **Practical Malware Analysis** and **The Antivirus Hacker's Handbook** for end-to-end defense.

## 10. Programming & Secure Coding

- **The C Programming Language (2nd Edition)** by Kernighan & Ritchie — foundational C literacy.
- **C++ for Hackers** by Steve Oualline — C++ concepts framed for security engineers.
- **Best Book to Master C++ Programming** by Bjarne Stroustrup — deep dive into C++.
- **Advanced Data Structures in C++** by Peter Brass — algorithmic grounding.
- **Sockets in C** and **Programmer's Guide to NCurses** by Dan Gookin — system programming utilities.

## 11. Scripting, Tooling & Automation

- **Black Hat Python** by Justin Seitz (2014) & by Justin Seitz & Tim Arnold (2021) — offensive python automation and tooling.
- **50 Useful Python Scripts** — small, actionable automation examples.
- **Python Crash Course** by Eric Matthes — beginner-friendly Python primer.
- **Python Notes for Professionals** (GoalKicker) — reference-style recap of core concepts.
- **Python Complete Notes** by QuantInsti & **Coding Games in Python** — practice-heavy reinforcement.
- **Black Hat Bash** by Dolev Farhi & Nick Aleks — shell scripting for offensive and automation scenarios.
- **Coding for Penetration Testers** — revisit for cross-language tooling guidance.

## 12. Browser & Client-Side Security

- **The Browser Hacker's Handbook** — central guide to browser attack surfaces.
- **HTML, CSS: Design and Build Websites** by Jon Duckett — web presentation fundamentals.
- **HTML5 Canvas** — graphics and scriptable canvas insight for client-side attack surface.
- **The Web Application Hacker's Handbook** & **XSS Sheet** — practical payload design.

## 13. Social Engineering & Human Factors

- **Social Engineering: The Art of Human Hacking** by Christopher Hadnagy — reconnaissance and manipulation tactics.
- **The Science of Human Hacking** by Chris Hadnagy — data-driven perspective on social engineering.

## 14. Specialized / Miscellaneous Extras

- **Real-World Bug Hunting** & **Web Hacking 101** — applied bounty hunting stories and workflows.
- **The Antivirus Hacker's Handbook** & **The Art of Computer Virus Research and Defense** — advanced malware/AV research.
- **Metasploit: The Penetration Tester's Guide** & **The Hacker Playbook 3** — offensive toolsets and playbooks.
- **VS Code Shortcuts** — productivity booster for building and testing tooling quickly.
- **Top 40 Python Interview Questions & Answers** — prep for technical interviews.

---

## 15. Suggested Learning Path

**Foundations & Prerequisites**

- Networking: start with **CCNA 200-301** or the higher-level overview in **TCP/IP in C**.
- Linux & Shell: pair the repository with **Linux Basics for Hackers** and **Linux Command Line and Shell Scripting** (add these locally if missing).
- Programming: **Python Crash Course** for scripting, then **The C Programming Language** for systems depth.

**Core Offensive & Defensive Skills**

- Web Focus: **Web Hacking 101** → **The Web Application Hacker's Handbook** → **OWASP Testing Guide**.
- Pentesting: **The Basics of Hacking and Penetration Testing** → **The Hacker Playbook 3** → **Metasploit Guide**.

**Specialization Tracks**

- Exploit Dev & Reverse Engineering: **Art of Exploitation** → **Shellcoder's Handbook** → **Practical Reverse Engineering** → **Practical Malware Analysis**.
- Mobile: **Android Hacker's Handbook** → **Mobile Application Hacker's Handbook** → **Android Malware Handbook**.
- Malware Analysis & Defense: **Practical Malware Analysis** → **Antivirus Hacker's Handbook** → **Art of Computer Virus Research and Defense**.
- Network Defense: **Practice of Network Security Monitoring** → **Cybersecurity Playbook** → add log analysis practice sets.

**Advanced & Research**

- Dive into **Advanced Penetration Testing**, **Advanced SQL Injection**, **Black Hat Python**, **Black Hat Bash**, and current research papers once core skills feel comfortable.

## Quick Tips

- Anchor your workflow in **Python** and **Linux basics**; most tooling and labs assume both.
- Use the **OWASP Testing Guide** alongside **The Web Application Hacker's Handbook** when targeting web apps.
- For exploit development, expect to invest serious time into **C**, assembly, and operating system internals.
- Hold off on malware reverse engineering titles until debugging, disassembly, and assembly feel natural.
- Document lab work as you go; these books are dense and repetition cements knowledge.

## Contributing

- Spot a missing cornerstone title? Open an issue or submit a PR with the book name, author, and why it matters.
- Found a better resource order or new edition? Share your reasoning so others can benefit.
- Keep notes concise and tied to the title—this project is about clarity over verbosity.

Knowledge should be accessible. Welcome aboard, and happy studying.
