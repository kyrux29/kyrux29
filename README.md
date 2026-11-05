<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=26&pause=1000&color=38BDF8&center=true&vCenter=true&width=720&lines=Qu%E1%BB%91c+Kh%C3%A1nh;Offensive+Security+Researcher;Whitebox+Auditing+%7C+Web+Exploitation" alt="Typing SVG" />

  <p>
    <a href="https://kyrux29.github.io/web-blog/">
      <img src="https://img.shields.io/badge/Blog-Security_Research-0f172a?style=flat-square&logo=astro&logoColor=ff5d01" alt="Blog" />
    </a>
    <a href="https://linkedin.com/in/your-profile">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:your-email@example.com">
      <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
    </a>
  </p>
</div>

---

## About

Computer Engineering student at **Hanoi University of Science and Technology (HUST)**.  
Member of **BKSEC** — Web Exploitation team.

I focus on **whitebox code auditing** and **web application security**. I prefer tracing untrusted input to dangerous sinks and understanding root-cause architectural issues rather than surface-level bugs.

Research and write-ups: [Security Blog](https://kyrux29.github.io/web-blog/)

---

## Vulnerability Research

### CVE-2026-115585 — pypdf

<div align="center">
  <img src="https://img.shields.io/badge/Severity-High_7.1-critical?style=flat-square" />
  <img src="https://img.shields.io/badge/CWE--400-Uncontrolled_Resource_Consumption-red?style=flat-square" />
  <img src="https://img.shields.io/badge/CWE--407-Inefficient_Algorithmic_Complexity-orange?style=flat-square" />
</div>

**Discovered and reported** a denial-of-service vulnerability in pypdf’s cross-reference parsing.

An incomplete remediation for repeated malformed cross-reference entries allowed crafted PDFs to force repeated full stream reloads, even when a recovery cache was present. This produced extremely long runtimes and a practical DoS condition. Fixed in `pypdf` 6.21.2.

- Advisory: [GHSA-jr96-gvgh-j3r4](https://github.com/advisories/GHSA-jr96-gvgh-j3r4)
- CVE: [CVE-2026-115585](https://www.cve.org/CVERecord?id=CVE-2026-115585)

---

## Competitive Security

- Active CTF player with **BKSEC** (HackTheOn Sejong, KalmarCTF, UMASS CTF, Dreamhack)
- Author of web exploitation challenges based on real-world vulnerabilities

---

## Technical Focus

**Languages**  
Python · Go · JavaScript/TypeScript · C/C++ · Java · PHP

**Security & Infrastructure**  
Linux · Docker · Burp Suite · Nginx · PostgreSQL · MongoDB · Redis

---

## GitHub Activity

<div align="center">
  <img height="155em" src="https://github-readme-stats.vercel.app/api?username=kyrux29&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true" />
  <img height="155em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kyrux29&layout=compact&theme=github_dark&hide_border=true&langs_count=6" />
</div>
