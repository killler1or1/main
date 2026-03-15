# Network Privacy & Homelab Tools

This repository contains a collection of **projects, tools, and resources** related to network privacy, DNS filtering, and homelab infrastructure.

The goal of this repository is to provide reusable resources that help improve:

- Network privacy
- Security
- DNS filtering
- Self-hosted infrastructure
- Homelab environments

Some projects in this repository are standalone, while others are designed to work with existing tools such as **DNS blockers, firewalls, hypervisors or network monitoring systems**.

---

# Repository Structure

The repository is organized into **independent subprojects**.

```
/
├─ README.md
│
├─ pihole/
│  ├─ ads.txt
│  ├─ tracking.txt
│  ├─ porn.txt
│  └─ adult-subscription-platforms.txt
│
└─ other-projects/
```

Each folder represents a **separate project or resource collection**.

---

# Projects

## Pi-hole Blocklists

The `pihole` directory contains blocklists formatted specifically for **Pi-hole**.

These lists help block:

- advertisements
- user tracking
- telemetry
- malicious domains

**Generic Blocklists**

The `blocklists` directory contains **generic domain lists** that can be used with various DNS filtering solutions.

Possible compatible tools include:

- Pi-hole
- AdGuard Home
- NextDNS
- Unbound DNS
- hosts-based filters
- firewall DNS filters

These lists may be provided in a **simpler domain-only format**.

---

# Disclaimer

The domains contained in the Projects originate from multiple sources, including:

- manual research
- publicly available blocklists
- community contributions
- AI-assisted generation

While efforts are made to avoid false positives, blocking certain domains may cause some services or websites to malfunction.

Use these resources **at your own risk**.

---

# Future Plans

This repository may include additional projects in the future, such as:

- DNS filtering tools
- homelab automation scripts
- network security utilities

---

# License

This project is released under the **MIT License**.

---

# Support

If you find this repository useful:

⭐ Consider starring the project  
🐛 Report issues  
🔧 Contribute improvements
