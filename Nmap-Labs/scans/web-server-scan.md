# Web Server Scan

## Objective

Identify and enumerate an HTTP service running on the target machine.

---

## Command Used

```bash
nmap -sV -p 8000 192.168.56.1
```

---

## Methodology

A Python HTTP server was started on the Windows host and scanned from Kali Linux.

---

## Findings

- Port 8000 was found open.
- HTTP service was identified successfully.

---

## Learning Outcome

- Learned targeted port scanning.
- Learned service version detection.
- Understood HTTP service enumeration.

---

⚠️ Performed in an authorized lab environment.
