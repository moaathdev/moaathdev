<div align="center">

# Moaath

**Security-minded developer** — I build small, readable tools for network defence and web apps.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)

</div>

---

## About

I like problems where correctness matters more than cleverness. Most of my work sits in two places:

- **Network security in Python** — packet parsing, detection logic, alerting. No magic libraries; I'd rather read the bytes myself.
- **Full-stack web apps** — Flask or PHP, from the data model to a real deployment.

I try to hold every project to the same bar: **no hidden dependencies, explicit logic, and documentation that tells the truth about limitations.**

---

## Featured projects

### [IDS Shield](https://github.com/moaathdev/ids-shield)

A dependency-free Intrusion Detection System for Windows, built on raw sockets.

- Detects TCP `SYN` / `FIN` / `XMAS` / `NULL` scans, UDP sweeps and ICMP ping floods
- Per-source sliding windows, with independent state for ICMP so one protocol can't mask another
- Two-stage alarm cooldown, idle-source reaping, fragment-aware parsing
- 16 unit tests and a GitHub Actions CI matrix

`Python` · `raw sockets` · `detection logic`

### [Student Attendance System](https://github.com/moaathdev/studentweb)

A Flask application for tracking student attendance, lectures and timetables, with an Arabic RTL interface.

- Role-based access for admins and students, with auto-generated per-student codes
- Attendance marking with explicit-save and unsaved-changes warnings
- Lecture file upload/download, timetable management, live statistics
- Deployment-ready: `render.yaml`, `Procfile`, environment-variable config

`Python` · `Flask` · `deployment`

---

## Toolbox

```text
Languages   Python · PHP · SQL · JavaScript · Bash
Frameworks  Flask
Data        MySQL · SQLite · JSON
Tooling     Git · GitHub Actions · ruff · Render
Systems     Windows · Linux
```

---

## Currently

- **Learning** detection engineering — moving from fixed thresholds toward real rules (Sigma-style thinking)
- **Refactoring** the single-file Flask app into blueprints, with tests
- **Reading** network traffic byte by byte, one header at a time

---

<div align="center">

*I document limitations as carefully as features — a tool that hides its edges is a tool you can't trust.*

</div>
