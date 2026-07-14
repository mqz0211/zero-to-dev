#  Cybersecurity Specialist Roadmap

**For people who want to:** break, defend, and secure systems — legally
and ethically.
**Estimated time (part-time):** 8–12 months to internship-ready.

>  **Ethics first.** Every technique in this roadmap is meant to be
> practiced only on systems you own or are explicitly authorized to
> test (your own lab, a CTF, or a bug-bounty program's defined scope).
> Unauthorized access to systems is illegal in most countries, full stop.

## Stage 0 — Fundamentals (2–3 weeks)
- [ ] [Computer basics](../FUNDAMENTALS/computer-basics.md)
- [ ] [Linux / command line basics](../FUNDAMENTALS/linux.md) — you will
      live in a terminal in this field
- [ ] [How the internet works](../FUNDAMENTALS/networking.md)
- [ ] [Problem-solving mindset](../FUNDAMENTALS/problem-solving.md)

## Stage 1 — Networking, properly (4 weeks)
Security is built on top of networking — you can't secure what you
don't understand.
- [ ] The OSI model and TCP/IP
- [ ] IP addresses, DNS, ports, and protocols (HTTP/HTTPS, FTP, SSH)
- [ ] How firewalls and VPNs work
- [ ] Packet capture basics (Wireshark)

## Stage 2 — Linux mastery (4 weeks)
- [ ] File permissions and users/groups
- [ ] Processes, services, and cron jobs
- [ ] Bash scripting for automation
- [ ] Log files — where they live and how to read them

**Practice:** [OverTheWire Bandit](https://overthewire.org/wargames/bandit/)
(free) — a genuinely excellent hands-on Linux/security starter wargame.

## Stage 3 — How the web actually works, then how it breaks (6 weeks)
- [ ] HTTP requests/responses, cookies, sessions
- [ ] The OWASP Top 10 (SQL injection, XSS, IDOR, SSRF, broken auth, etc.)
- [ ] How to read and modify requests (Burp Suite Community Edition)
- [ ] Authentication vs. authorization (and why conflating them causes bugs)

**Practice:** [PortSwigger Web Security Academy](https://portswigger.net/web-security)
— free, hands-on labs for every OWASP Top 10 category.

## Stage 4 — Hands-on practice environments (ongoing from here)
- [ ] Set up a home lab with VirtualBox/VMware + Kali Linux
- [ ] Solve beginner CTF challenges — [TryHackMe](https://tryhackme.com)
      (free tier) and [Hack The Box](https://www.hackthebox.com) (free tier)
- [ ] Build your own small vulnerable app to attack — see the
      `CyberRange-Lite`-style project idea in
      [`PROJECTS/advanced-projects.md`](../PROJECTS/advanced-projects.md)

## Stage 5 — Pick a specialization (6–8 weeks)
Security splits into distinct tracks — try a few before committing:
- [ ] **Offensive (red team / pentesting):** exploitation, privilege
      escalation, report writing
- [ ] **Defensive (blue team / SOC):** log analysis, SIEM tools,
      incident response, digital forensics
- [ ] **AppSec:** secure code review, threat modeling, working with dev teams
- [ ] **GRC (governance, risk, compliance):** frameworks like ISO 27001,
      less hands-on-keyboard, more policy and process

## Stage 6 — Certifications & credibility (ongoing)
Not required to start, but they matter for job applications:
- [ ] Entry-level: CompTIA Security+
- [ ] Practical/offensive: eJPT (cheaper, hands-on) → OSCP (harder, gold standard)
- [ ] Cloud security: AWS/Azure security certifications once you know a cloud platform

## Stage 7 — Build a portfolio (ongoing)
Security portfolios look different from software portfolios:
- [ ] Write-ups of CTF challenges you've solved (with permission/public ones)
- [ ] A home-lab project on GitHub (e.g., a detection rule set, a small
      security tool, a documented pentest of your own lab)
- [ ] A blog or GitHub repo explaining a vulnerability class in your own words
- [ ] See [`CAREERS/portfolio.md`](../CAREERS/portfolio.md)

##  You're ready for an internship/junior role interview when you can:
- Explain SQL injection well enough that a non-technical person understands the risk
- Walk through how you'd approach an unfamiliar target within an authorized scope
- Talk through a CTF challenge you solved, including what you tried that *didn't* work

## Resources for this path
- [Free courses →](../RESOURCES/free-courses.md)
- [Books →](../RESOURCES/books.md)
- [YouTube channels →](../RESOURCES/youtube.md)
- [Websites & tools →](../RESOURCES/websites.md)
