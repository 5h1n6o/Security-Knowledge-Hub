
# 🏛 Security Knowledge Hub  
**総合セキュリティ学習ポータル（Pentest / Red Team / CTF / Blue Team / Cloud / Tools）**

このリポジトリは、以下の分野の個人的な学習メモです。

- Penetration Testing（攻撃・侵入テスト）  
- Red Team Operations（攻撃演習・戦略）  
- CTF（Crypt / Forensics / Pwn / Reverse / Web / Misc）  
- Blue Team（DFIR / Threat Hunting / SOC）  
- Cloud Security（AWS / Azure / GCP）  
- Secure Coding / DevSecOps  
- Tools（Burp / Wireshark / Ghidra / pwntools / Volatility）

各分野は **専用リポジトリ**として独立管理し、  
このポータルから体系的にアクセスできるようにしています。

---

# 📘 1. Fundamentals（基礎）
- 法的・倫理的ガイドライン（RoE / 許可範囲 / 証跡保全）
- ラボ環境構築（VMware / Kali / Sysmon / ELK）
- Linux / Windows 基本コマンド
- ネットワーク基礎（nmap / tcpdump / Wireshark）
- 暗号・認証・プロトコル基礎

---

# 🛡 2. Penetration Testing（攻撃・侵入テスト）
> MITRE ATT&CK に沿った体系的な Pentest リポジトリ

**リポジトリ：**  
👉 `https://github.com/5h1n6o/Ethical-Hacking-Resources` [(github.com in Bing)](https://www.bing.com/search?q="https%3A%2F%2Fgithub.com%2F5h1n6o%2FEthical-Hacking-Resources")

### 章構成
- OSINT（情報収集）  
- Reconnaissance（偵察）  
- Resource Development（リソース開発）  
- Initial Access（初期侵入）  
- Execution / Persistence / PrivEsc  
- Defense Evasion  
- Credential Access  
- Discovery  
- Lateral Movement  
- Collection  
- Command & Control  
- Exfiltration  
- Impact  

---

# 🔴 3. Red Team Operations（レッドチーム演習）
> 組織の防御力を評価するための総合攻撃演習

### 3.1 Methodology  
- Threat Modeling  
- Kill Chain / ATT&CK ベースの攻撃設計  
- Purple Team 連携  

### 3.2 Campaign Planning  
- 目的設定（Crown Jewel / Detection Gaps）  
- 攻撃シナリオ設計  
- RoE（Rules of Engagement）  

### 3.3 Initial Access  
- フィッシングキャンペーン  
- 物理侵入（Badge Cloning / Tailgating）  
- 社会工学（OSINT → 誘導）  

### 3.4 Long-term Operations  
- C2 Infrastructure  
- EDR 回避  
- ログ回避  
- 権限昇格 → 横展開 → 目的達成  

### 3.5 Reporting  
- 攻撃シナリオの再現  
- 防御側の検知ポイント  
- 改善提案（Detection Engineering）

---

# 🎮 4. Capture The Flag（CTF）
CTF はジャンルごとに体系が異なるため、**分野別リポジトリ**として整理。

## 🔐 Cryptography  
👉 `CTF-Cryptography`  
- RSA / ECC / AES  
- Hash / OTP  
- Tools: sage / RsaCtfTool  

## 🧬 Forensics  
👉 `CTF-Forensics`  
- Memory / Disk / Network  
- Steganography  
- Tools: Volatility / Wireshark  

## 🧱 Pwnable  
👉 `CTF-Pwn`  
- Stack / Heap  
- ROP / Format String  
- Tools: pwntools / gdb / gef  

## 🔍 Reverse Engineering  
👉 `CTF-Reverse`  
- Static / Dynamic  
- Malware  
- Tools: Ghidra / IDA / radare2  

## 🌐 Web  
👉 `CTF-Web`  
- SQLi / XSS / SSRF  
- Template Injection  
- Tools: Burp / ffuf  

## 🎲 Misc  
👉 `CTF-Misc`  
- Encoding  
- OSINT  
- Puzzle  

---

# 🔵 5. Blue Team（防御・解析）
- DFIR（Digital Forensics & Incident Response）  
- Threat Hunting  
- Malware Analysis  
- Log Analysis（Sysmon / ELK / LimaCharlie）  
- Detection Engineering（Sigma / YARA）  
- SOC 運用  

---

# ☁️ 6. Cloud Security
- AWS IAM / Networking / Attack Paths  
- Azure AD / Conditional Access  
- GCP IAM / Workload Identity  
- Cloud Pentest  
- Cloud DFIR  

---

# 🧪 7. Tools & Cheat Sheets
- Burp Suite  
- Wireshark  
- Ghidra / IDA  
- pwntools  
- Volatility  
- impacket  
- ffuf / gobuster  
- Sysinternals Suite  

---

# 🗺 8. Learning Roadmap（学習ロードマップ）

## Pentest Roadmap
1. Networking  
2. Linux / Windows  
3. Web Security  
4. AD / Lateral Movement  
5. C2 / Evasion  
6. Reporting  

## CTF Roadmap
1. Web / Crypto  
2. Reverse  
3. Pwn  
4. Forensics  
5. Misc  

## Red Team Roadmap
1. Threat Modeling  
2. OSINT  
3. Initial Access  
4. Long-term Ops  
5. Reporting  

## Blue Team Roadmap
1. Log Analysis  
2. DFIR  
3. Threat Hunting  
4. Detection Engineering  

---

# 📚 9. References & Resources
- OWASP  
- MITRE ATT&CK  
- NIST SP800  
- Awesome Lists  
- Security Blogs  
- Tools Documentation  

---



