# 🦀 RustyReverser

**RustyReverser** is a hands-on learning project where I explore Rust through the lens of malware analysis and simulation. The goal is to build a modular set of **safe, educational malware-like behaviors** written in Rust and use them to develop skills in static/dynamic analysis, reverse engineering, and security tooling.

---

## 🎯 Project Goals

- 🔧 Learn Rust by building real-world inspired simulation tools
- 🕵️ Mimic malware techniques in a safe & controlled way (no actual malicious behavior)
- 🔍 Practice reverse engineering using tools like Ghidra, Cuckoo, and FLARE VM
- 📚 Build a personal knowledge base around Rust-based malware traits
- 📎 Showcase a project aligned with advanced research in malware and Rust

---

## 🛠️ Modules (Planned)

| Module                | Description                                       | Status     |
|----------------------|---------------------------------------------------|------------|
| Learning Rust       | Learn the basics of Rust | ✅ In Progress |
| Anti-Debugging        | Detect debugger presence using timing tricks, syscall flags | 🔜 Planned |
| File Enumeration      | Recursively scan files/directories                | 🔜 Planned |
| C2 Simulation         | Simulate basic beaconing to a fake command server | 🔜 Planned |
| Obfuscation Techniques| Add control-flow obfuscation and code mutations   | 🔜 Planned |
| Self-Unpacking Logic  | Simulate encrypted payloads and runtime unpacking | 🔜 Planned |

Each module will include:
- Source code (`src/modules/`)
- Logs and outputs
- Reverse engineering writeups in `docs/analysis_reports/`

---

## 🧠 Learning Plan

This project is my entry point into Rust, designed to be modular and beginner-friendly. Here’s the rough roadmap I’m following:

### 📅 Month 1: Fundamentals
- ✅ Learn Rust basics (variables, functions, ownership)
- ✅ Build a simple CLI with `cargo`
- ✅ Add anti-debugging sleep trick

### 📅 Month 2: Intermediate
- Add filesystem traversal
- Learn about modules and error handling
- Implement log writing and environment detection

### 📅 Month 3+: Reverse Engineering & Analysis
- Compile with `--release`, inspect binaries in Ghidra
- Run samples in sandboxes
- Benchmark AV/sandbox detection
- Write YARA rules for Rust binaries

---

## 🧪 Tools & Stack

- **Language:** Rust 🦀
- **Editor:** VS Code + rust-analyzer
- **RE Tools:** Ghidra, Cutter, FLARE VM, Cuckoo Sandbox
- **Crates:** `chrono`, `reqwest`, `simplelog`, `rand`, etc.
- **OS:** Linux & Windows (VM)

---

## 📚 Docs & Reports

Check `docs/analysis_reports/` for detailed breakdowns of each module, including:
- Static/dynamic analysis
- Reverse engineering process
- Lessons learned from Rust’s compilation and structure

---

## 📸 Screenshots & Examples

(Coming soon — Ghidra screenshots, terminal logs, sandbox outputs)

---

## ⚠️ Disclaimer

This project is strictly for **educational and research purposes**.  
No actual malicious activity is implemented or encouraged.  
All modules are simulations intended for safe environments and learning only.

---

## 📌 Inspiration

This project aligns with my interest in malware analysis, reverse engineering, and the evolving landscape of Rust-based threats. It's also an early exploration for a potential PhD theme around the concept of a **Rust-based malware repository** for academic analysis.

---

## 👤 Author

**Augustin Renard**  
MSc Applied Cyber Security @ Heriot-Watt University  
🔗 [Portfolio](https://augmaster.github.io)  
🔗 [LinkedIn](https://linkedin.com/in/augustin-renard-986855179)

---

## 🌱 Contributions

This is a solo learning project for now, but feel free to fork, star, or suggest improvements!
