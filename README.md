# ⬡ CYBER NET LAB
### *One HTML file. No install. Just open it and your brain explodes.* 🧠💥

---

> 💬 *"What if subnetting, DNS, TCP, and HTTP all finally made sense — tonight?"*

You've been putting off networking. The docs are boring. The videos are slow. This isn't either of those things.

**CYBER NET LAB** is a single `.html` file that runs entirely in your browser — no npm, no Python, no server — and teaches you everything that gets asked in cyber security interviews through **live terminals, animated diagrams, and real Kali Linux commands.**

```bash
git clone https://github.com/yourusername/cyber-net-lab
open cyber-lab.html   # that's it. seriously.
```

---

## 🔥 What's waiting inside

| 🧩 | What you'll find |
|---|---|
| 🌐 **IPv4 Deep Dive** | Click octets live · binary auto-updates · packet header SVG · class diagram · private ranges |
| 📐 **CIDR Calculator** | Type any subnet → get everything · binary mask visualiser · /0 to /32 scale |
| 🔮 **IPv6 Explained** | Why we ran out of IPs · address parser · *"3.4 × 10³⁸ addresses"* — what that actually means |
| 🔗 **TCP vs UDP** | Animated 3-way handshake · SYN flood attack · TCP flags · `tcpdump` output |
| 🔌 **Port Heat Map** | Colour-coded risk grid · click any port · why port 6379 open = instant breach |
| 📡 **DNS Resolution** | Animated tree: Browser → Root NS → TLD → Answer · `dig` · subdomain takeover attack |
| 🔐 **HTTP & HTTPS** | TLS handshake · curl builder · 14 status codes · security headers · `nikto` |
| ⚔️ **10 Live Challenges** | Type answers in terminal · earn XP · hints available · Beginner → Elite Hacker |

---

## 🖥️ 6 Live Kali Terminals — Try These Right Now

```bash
# IPv4 Lab
ip addr show        ping 8.8.8.8        ipcalc 10.0.0.0/8

# CIDR Lab
ipcalc 192.168.1.0/24      subnets 10.0.0.0/24 4

# IPv6 Lab
why ipv6            compare             ip -6 addr show

# TCP Lab
tcpdump -i eth0     netstat -tulnp      syn flood

# DNS Lab
dig google.com A    dnsenum example.com     attack dangling

# HTTP Lab
curl -v https://google.com    nikto -h target    tls explain
```

---

## ⚔️ Challenges — Can You Score 1500 XP?

```
challenge@kali:~# challenge 5
Q: Name the three packets in a TCP connection setup in order.

challenge@kali:~# hint
💡 SYN → ? → ? Three letters each...

challenge@kali:~# answer syn syn-ack ack
✓ CORRECT! +150XP  →  Explanation unlocked
```

10 challenges. EASY 🟢 → MEDIUM 🟡 → HARD 🔴. Topics: subnetting, CIDR, DNS records, TCP, ports, HTTP status codes, DNS attacks. Every wrong answer teaches you something.

---

## 🧠 After this you'll finally know...

✅ How many hosts are in a `/26` — without Googling  
✅ What `0.0.0.0/0` in an AWS Security Group actually means  
✅ The 5 hops a DNS query takes before your page loads  
✅ Why port `3306` open to the internet = database breach waiting to happen  
✅ What TLS negotiates before a single byte of HTTPS is sent  
✅ How attackers hijack subdomains using deleted S3 buckets  
✅ The difference between `401` and `403` (it comes up in every interview)

---

## 📁 Entire repo is one file

```
cyber-net-lab/
├── 📄 cyber-lab.html   ← everything. 120KB. zero dependencies.
└── 📖 README.md
```

No React. No bundler. No build step. SVG diagrams, terminal engine, CIDR calculator, challenge system — all vanilla JS inside one file you can inspect, fork, and learn from.

---

## 🎯 Built for

🎓 Students cramming before interviews &nbsp;·&nbsp; 🔐 Pentesters filling knowledge gaps  
☁️ Cloud devs who copy-paste VPC configs &nbsp;·&nbsp; 🐞 Bug hunters learning recon  
👨‍💻 Self-taught devs networking was never taught &nbsp;·&nbsp; 🧑‍🏫 Teachers who want something actually good

---

⭐ **Star it if networking finally clicked.** Someone else needs to find this too.

*MIT — fork it, teach with it, break it.*
