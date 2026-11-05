<div align="center">
  <h1>Quốc Khánh</h1>
  <h3>Offensive Security Researcher</h3>
  <p>
    <a href="https://kyrux29.github.io/web-blog/">Blog</a> •
    <a href="https://linkedin.com/in/your-profile">LinkedIn</a> •
    <a href="mailto:your-email@example.com">Email</a>
  </p>
</div>

---

## About

Computer Engineering student at **Hanoi University of Science and Technology (HUST)**.  
Member of **BKSEC** (HUST Information Security Club) — Web Exploitation team.

I focus on **whitebox code auditing**, **web application security**, and **vulnerability research**. My work centers on tracing untrusted input to dangerous sinks, identifying architectural flaws, and understanding root causes rather than surface-level bugs.

I write technical research and CTF write-ups on [my blog](https://kyrux29.github.io/web-blog/).

---

## Vulnerability Research

### CVE-2026-115585 — pypdf

| | |
|---|---|
| **Severity** | High (7.1) |
| **Type** | Uncontrolled Resource Consumption (CWE-400) / Inefficient Algorithmic Complexity (CWE-407) |
| **Impact** | Denial of Service via crafted cross-reference streams |
| **Status** | Fixed in pypdf 6.21.2 |
| **Advisory** | [GHSA-jr96-gvgh-j3r4](https://github.com/advisories/GHSA-jr96-gvgh-j3r4) |

Discovered and reported a vulnerability in pypdf’s cross-reference parsing. An incomplete remediation for repeated malformed cross-reference entries allowed crafted PDFs to force repeated full stream reloads, even when a recovery cache was present. This resulted in extremely long runtimes and a practical denial-of-service condition.

This was a follow-up to a previous incomplete fix. The root cause lay in the interaction between the recovery logic and the cross-reference stream parser.

---

## Competitive Security & Challenge Development

- Active CTF player with **BKSEC** (HackTheOn Sejong, KalmarCTF, UMASS CTF, Dreamhack)
- Author of web exploitation challenges based on real-world vulnerabilities

---

## Technical Focus

**Languages**  
Python, Go, JavaScript/TypeScript, C/C++, Java, PHP

**Security & Infrastructure**  
Linux, Docker, Burp Suite, Nginx, PostgreSQL, MongoDB, Redis

**Areas of Interest**  
- Whitebox code auditing  
- Web application security  
- Source-to-sink analysis  
- Architectural vulnerability research  

---

## GitHub Activity

<div align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=kyrux29&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true" />
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kyrux29&layout=compact&theme=github_dark&hide_border=true&langs_count=6" />
</div>
