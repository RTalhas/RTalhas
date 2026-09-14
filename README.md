# Hi, I'm Rodrigo Talhas 👋

Computer Science & Engineering graduate from **Universidade da Beira Interior (UBI)**, now doing a **Master's in Cybersecurity**.
I like building things that run on my own hardware and then figuring out how to break them and how to secure them.

- 🔐 Interested in **cybersecurity**, **AI**, and where the two meet
- 🖥️ Running a **Proxmox homelab** for self-hosting and security labs
- 🌱 Currently learning: offensive security labs, hardening, and automating infrastructure
- 📍 Covilhã, Portugal

## 🛠️ Projects

**[Projeto_VM](https://github.com/RTalhas/Projeto_VM): Anomaly detection in virtual machines with vision-language models** *(BSc final project, UBI · graded 18/20)*
Detects anomalous behaviour in Linux VMs by turning system state into images and asking a VLM to classify them, with no model training (inference only).
- Captures 20 system metrics with `psutil` (CPU, memory, network, processes…) and encodes them as a 64×64 grayscale "visual fingerprint"
- Generates a labelled dataset by stressing the CPU, memory, network and processes
- Benchmarks **Qwen2.5-VL, LLaVA and Moondream** locally through **Ollama**, comparing no-context, zero-shot and few-shot prompting

**TalhasBorg: Discord bot for a self-hosted game server**
A Python (`discord.py`) bot that manages a modded Minecraft server running in an LXC container on Proxmox.
- Start / stop / restart the server with confirmation flows, plus live player and performance status
- Admin tools over **RCON** (whitelist, kick, ban, broadcast)
- Host monitoring through the **Proxmox VE API**: CPU, RAM, temperatures, SMART, storage, and 24h charts
- Built with **least privilege** in mind: scoped API tokens, restricted commands, input validation, and a dedicated unprivileged service user

**Homelab**
Proxmox VE on a small server: LXC containers, systemd services, automated backups, remote access through Tailscale, and no ports opened on the router.
Next up: an isolated network bridge for a Kali + vulnerable-targets lab.

## 🧰 Tech

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat&logo=debian&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat&logo=kalilinux&logoColor=white)

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rodrigo-talhas-b10537379/)
