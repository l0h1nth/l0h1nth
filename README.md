# Lohinth M


I play CTFs and build small security projects to learn how real vulnerabilities work.
Interested in web exploitation, Linux internals, forensics, and defensive security.

---

## About

```text
role        aspiring cybersecurity analyst / blue team engineer
focus       Linux security, EDR concepts, SIEM workflows, detection rules
learning    Rust, Python, Bash, networking, malware behavior basics
style       quiet tools, clear logs, reproducible labs
```
---

## Open Source Contributions

### Odysseus
Self-hosted AI workspace for local-first chat, agents, documents, memory, email, calendar, and model serving.

- Hardened multi-user document tool owner scoping so agent document tools cannot list, read, edit, suggest against, or delete another user’s documents.
- Fixed a companion pairing route runtime `NameError` by restoring the missing admin guard import.
- Added focused regression tests for owner isolation and companion pairing route behavior.

Merged PRs:
- `#618` Harden document tool owner scoping
- `#927` Fix companion pairing admin guard import
  

## Current Project

### Mini Linux EDR Agent

A small defensive endpoint monitoring agent for Linux. It watches process activity, sensitive file changes, network sockets, and common persistence locations, then writes alerts as JSON Lines.

```text
stack       Rust, Linux /proc, notify, TOML, JSONL
goal        understand endpoint telemetry and detection logic
status      active learning project
```

Repository: `https://github.com/l0h1nth/mini-linux-edr`

---

## Skills

```text
systems     Linux, Bash, processes, filesystems, services
security    detection engineering, log analysis, persistence checks
coding      Rust, Python, shell scripting
tools       Git, GitHub, cargo, nmap, tcpdump, Wireshark, journalctl
```

---

## Featured Work

| Project | What it does | Tech |
| --- | --- | --- |
| Mini Linux EDR | Linux endpoint monitoring and JSONL alerts | Rust, Linux |
| Detection Rules | Simple rules for suspicious Linux behavior | TOML, Regex |
| Home Lab | Notes from defensive security experiments | Linux, Networking |

---

## GitHub Stats

![GitHub stats](https://streak-stats.demolab.com/?user=l0h1nth&theme=default&border=000000)

---

## Contact

```text
Mail lohinth25@proton.me

```

---

