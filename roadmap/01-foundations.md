# Phase 1: Foundations (8–10 weeks)

You can't secure what you don't understand. Nearly every security skill sits on
top of networking, operating systems, and a little scripting.

## 1. Networking (3 weeks)

Learn:
- OSI and TCP/IP models: know which layer a given protocol lives on
- IP addressing, subnetting, CIDR (`/24` = 256 addresses, 254 usable hosts)
- TCP vs. UDP, the three-way handshake (SYN → SYN/ACK → ACK)
- Core protocols and default ports: HTTP 80, HTTPS 443, SSH 22, DNS 53, SMTP 25, RDP 3389, SMB 445
- DNS resolution, DHCP, ARP, NAT, routing basics
- Firewalls, VLANs, VPNs at a conceptual level

Do:
- Install Wireshark, capture your own traffic, and find a DNS query, a TCP handshake, and a TLS Client Hello
- Run `ping`, `traceroute`/`tracert`, `nslookup`/`dig`, `netstat`/`ss` and explain each output

Resources (free): Professor Messer's Network+ videos, the Practical Networking
subnetting series on YouTube, TryHackMe "Pre Security" path.

## 2. Linux (3 weeks)

Learn:
- Filesystem layout (`/etc`, `/var/log`, `/home`, `/tmp`), permissions (`chmod 750`, SUID)
- Users, groups, `sudo`, processes (`ps`, `top`, `kill`), services (`systemctl`)
- Text tools: `grep`, `awk`, `sed`, `sort`, `uniq -c`, `cut`, `head`/`tail`, pipes
- Package management, SSH keys, cron

Do:
- Run Linux daily in a VM (VirtualBox + Ubuntu) or WSL2
- **OverTheWire Bandit** levels 0–20 (overthewire.org/wargames/bandit). This is the Phase 1 milestone.
- Practice log searching on `/var/log/auth.log` in your VM using only `grep`/`awk`/`sort`/`uniq`

## 3. Windows (1 week)

Learn: Active Directory concepts (domain, DC, users, groups, GPO), Event Viewer,
PowerShell basics, the registry, services, and why Event IDs 4624, 4625, 4688
and 4720 matter.

## 4. Python (2–3 weeks, ongoing)

Learn: variables, loops, functions, files, `dict`/`list`, the `socket`,
`hashlib`, `re`, `subprocess` and `requests` modules.

Do: every lab in this repo has a Python part. Automate anything you do twice.

Resources: *Automate the Boring Stuff with Python* (free online).

## Checkpoint

You're ready for Phase 2 when you can, without looking anything up:
- [ ] Explain what happens, layer by layer, when you type a URL into a browser
- [ ] Subnet `192.168.10.0/26` into its network, broadcast, and usable range
- [ ] Find the top 5 IPs in a log file with a single shell pipeline
- [ ] Write a Python script that reads a file and counts occurrences of a pattern
