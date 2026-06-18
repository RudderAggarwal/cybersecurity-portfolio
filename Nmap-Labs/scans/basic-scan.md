# Basic Nmap Scan

## Objective

Identify active hosts and enumerate services within an authorized lab environment.

---

## Tools Used

- Kali Linux
- Nmap

---

## Commands Used

### Basic Scan

```bash
nmap localhost
```

### Host Discovery

```bash
nmap -sn 192.168.56.1
```

### Basic Port Scan

```bash
nmap 192.168.56.1
```

### Service Version Detection

```bash
nmap -sV 192.168.56.1
```

---

## Methodology

A series of Nmap scans were performed to identify live hosts, open ports, and running services.

---

## Findings

- Host discovery successfully identified the Windows host.
- Basic port scanning was performed against the target.
- Service version detection was executed to enumerate running services.

---

## Screenshots

- scan1.png
- scan2-host-discovery.png
- scan3-basic-port-scan.png
- scan4-service-detection.png

---

## Learning Outcome

- Learned host discovery using Nmap.
- Understood basic port scanning.
- Learned service version detection using `-sV`.
- Practiced reconnaissance techniques in an authorized lab environment.

---

⚠️ All activities were performed in a controlled lab environment.
