<div align="center">

```
╔═══════════════════════════════════════════════════════════╗
║                                                           ║
║    ██████╗ ██╗  ██╗     ██╗ █████╗  ██████╗██╗  ██╗     ║
║   ██╔═████╗╚██╗██╔╝     ██║██╔══██╗██╔════╝██║ ██╔╝     ║
║   ██║██╔██║ ╚███╔╝      ██║███████║██║     █████╔╝      ║
║   ████╔╝██║ ██╔██╗ ██   ██║██╔══██║██║     ██╔═██╗      ║
║   ╚██████╔╝██╔╝ ██╗╚█████╔╝██║  ██║╚██████╗██║  ██╗     ║
║    ╚═════╝ ╚═╝  ╚═╝ ╚════╝ ╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝     ║
║                                                           ║
║         S E C U R I T Y   R E S E A R C H E R            ║
╚═══════════════════════════════════════════════════════════╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&size=16&duration=3000&pause=800&color=00D4FF&center=true&vCenter=true&width=600&lines=Security+Researcher+%26+Source+Code+Auditor;Memory+Exhaustion+%7C+Injection+%7C+Heap+Overflow;Node.js+%26+PHP+Ecosystem+Specialist;CVE+Author+%7C+PoC+Developer)](https://git.io/typing-svg)

</div>

---

<div align="center">

```
[ OPERATOR STATUS: ACTIVE ]  [ CLEARANCE: CVE AUTHOR ]  [ NODE: REMOTE ]
```

</div>

## `> whoami`

```bash
$ cat /etc/researcher.conf

NAME        : 0XJacks
ROLE        : Security Researcher & Source Code Auditor
FOCUS       : Logic Flaws · Resource Management · Memory Handling
ECOSYSTEM   : Node.js · PHP
TARGETS     : Core Libraries & Frameworks
STATUS      : [●] ACTIVE — Hunting Bugs
```

> *Specializes in identifying complex logic flaws and resource management vulnerabilities in core libraries and frameworks. Deep-dive analysis of memory handling and input sanitization mechanisms.*

---

## `> ls ./CVEs/`

<div align="center">

| `[!]` | CVE ID | Target Package | Vulnerability Class | Severity |
|:---:|:---|:---|:---|:---:|
| 🔴 | **CVE-2026-25762** | `@adonisjs/bodyparser` | Remote Memory Exhaustion (DoS) | ![Critical](https://img.shields.io/badge/CRITICAL-ff3c6e?style=flat-square&logoColor=white) |
| 🔴 | **CVE-2026-25755** | `jsPDF` *(Core)* | PDF Object Injection — Sandbox Escape | ![Critical](https://img.shields.io/badge/CRITICAL-ff3c6e?style=flat-square&logoColor=white) |
| 🟠 | **CVE-2026-25535** | `jsPDF` *(GIF Module)* | Resource Exhaustion — Heap Overflow | ![High](https://img.shields.io/badge/HIGH-ff8c00?style=flat-square&logoColor=white) |

</div>

<details>
<summary><code>> cat CVE-2026-25762.md</code></summary>

```
╔──────────────────────────────────────────────────────────╗
│  CVE-2026-25762  ·  CRITICAL                             │
├──────────────────────────────────────────────────────────┤
│  Package  : @adonisjs/bodyparser                         │
│  Class    : Remote Memory Exhaustion (DoS)               │
│  Vector   : Network / Unauthenticated                    │
│  Impact   : Server OOM crash via crafted request body    │
╚──────────────────────────────────────────────────────────╝
```

</details>

<details>
<summary><code>> cat CVE-2026-25755.md</code></summary>

```
╔──────────────────────────────────────────────────────────╗
│  CVE-2026-25755  ·  CRITICAL                             │
├──────────────────────────────────────────────────────────┤
│  Package  : jsPDF (Core)                                 │
│  Class    : PDF Object Injection (Sandbox Escape)        │
│  Vector   : Crafted PDF input                            │
│  Impact   : Escape execution sandbox via object inject   │
╚──────────────────────────────────────────────────────────╝
```

</details>

<details>
<summary><code>> cat CVE-2026-25535.md</code></summary>

```
╔──────────────────────────────────────────────────────────╗
│  CVE-2026-25535  ·  HIGH                                 │
├──────────────────────────────────────────────────────────┤
│  Package  : jsPDF (GIF Module)                           │
│  Class    : Resource Exhaustion (Heap Overflow)          │
│  Vector   : Malformed GIF input                          │
│  Impact   : Heap corruption leading to process crash     │
╚──────────────────────────────────────────────────────────╝
```

</details>

---

## `> cat ./skills/arsenal.txt`

**Languages & Environments**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Specialized Expertise**

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│  ▸ EXPLOIT DEVELOPMENT                                  │
│    └─ Crafted PoCs for OOM and Injection attacks        │
│                                                         │
│  ▸ SECURITY AUDITING                                    │
│    └─ Manual code review · Node.js & PHP ecosystems     │
│                                                         │
│  ▸ WEB SECURITY                                         │
│    └─ Bypassing complex sanitization layers & WAFs      │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## `> ping ./contact`

<div align="center">

[![ProtonMail](https://img.shields.io/badge/ProtonMail-8E8E93?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:ZeroXJacks@proton.me)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/ZeroXJacks)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@ZeroXJacks)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/ZeroXJacks)

</div>

---

<div align="center">
</div>
