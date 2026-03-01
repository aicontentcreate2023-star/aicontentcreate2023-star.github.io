# Bug Bounty 赏金任务整理报告

📄 **版本：** v1.0  
🕒 **最后更新：** 2026-03-01 19:30 GMT+8  
👤 **撰写：** 阿福 (一号)

---

## 📋 执行摘要

Bug Bounty（漏洞赏金）是一种"按效果付费"的安全测试模式，企业公开邀请安全研究员（白帽黑客）发现并报告软件漏洞，只为有效漏洞付费。本报告整理了主要平台来源、任务类型、难度评估、环境要求和金额范围。

---

## 🌐 一、主要平台来源

### 1. **HackerOne** ⭐⭐⭐⭐⭐
- **网址：** https://hackerone.com/
- **特点：** 最大的 bug bounty 平台之一，拥有 600k+ 已发现漏洞
- **项目数量：** ~450+ 活跃项目
- **优势：**
  - 高质量客户（Snapchat, Adobe, GitHub, Coinbase, Zoom, TikTok）
  - AI agent (Hai) 辅助 triage
  - 24/7 关键问题响应
  - Gold Standard 认证计划（最高信誉）
- **研究员数量：** 全球数十万名
- **已支付赏金：** 数亿美元
- **特色服务：**
  - AI Red Teaming（AI 安全测试）
  - Pentest as a Service（渗透测试即服务）
  - Bug Bounty Campaign（限时加倍赏金活动）

### 2. **Bugcrowd** ⭐⭐⭐⭐⭐
- **网址：** https://www.bugcrowd.com/
- **特点：** 第二大平台，强调持续性安全测试
- **评分：** 4.9/5（用户评价）
- **优势：**
  - 24/7 紧急响应
  - 降低 30% 被入侵风险
  - 找到 7 倍更多关键漏洞
  - 268% 投资回报率
  - 专业 triage 团队（减少 60% 工作量）
- **客户：** T-Mobile, Atlassian, HP, Motorola, NASA
- **服务类型：**
  - Bug Bounty
  - Vulnerability Disclosure Program (VDP)
  - Pen Testing as a Service
  - Red Team as a Service

### 3. **Intigriti** ⭐⭐⭐⭐
- **网址：** https://www.intigriti.com/
- **特点：** 欧洲领先平台，强调 GDPR 合规
- **研究员数量：** 125,000+
- **活跃项目：** 400+
- **已支付赏金：** €50M+
- **优势：**
  - 真正的欧盟数据主权
  - 军事级加密（唯一应用层加密的 bug bounty 平台）
  - 行业领先的 triage 速度和准确度
  - 灵活定价，无隐藏成本
- **客户：** Intel, Microsoft, Grafana, Personio
- **特色：** 最快增长的安全研究员社区

### 4. **YesWeHack** ⭐⭐⭐
- **网址：** https://www.yeswehack.com/
- **特点：** 法国起源，多渠道漏洞管理
- **优势：**
  - 统一管理来自 Bug Bounty, VDP, pentests, scanners 的漏洞
  - 仅为可操作的报告付费
  - 自动化和协作友好功能
- **定位：** 成本效益高的风险管理

### 5. **Immunefi** ⭐⭐⭐⭐ (Web3 专精)
- **网址：** https://immunefi.com/
- **特点：** Web3/区块链专用平台
- **保护资产：** $180B+
- **防止黑客损失：** $25B+
- **研究员：** 60,000+
- **安全协议：** 650+
- **客户：** zkSync, Aave, Puffer, Badger DAO, Lido
- **优势：**
  - 专注智能合约安全
  - Audit Competition 模式
  - Web3 Security Playbook

### 6. **其他平台**
- **Synack** - 精英研究员模式
- **Cobalt.io** - 敏捷渗透测试
- **Open Bug Bounty** - 免费公开披露平台
- **Disclose.io** - 漏洞披露政策目录

---

## 🎯 二、任务类型分类

### 1. **Bug Bounty Program (BBP)** 💰
- **描述：** 持续性赏金计划，任何时间可提交漏洞
- **付费模式：** 按漏洞严重程度付费
- **适合：** 
  - 想要长期稳定收入
  - 有专长领域（如 Web3, 移动应用）
  - 可自由安排时间

### 2. **Vulnerability Disclosure Program (VDP)** 📢
- **描述：** 公司接受漏洞报告，但不保证付费（可能给荣誉或小额赏金）
- **目的：** 建立安全反馈渠道
- **适合：** 
  - 新手练习
  - 建立声誉
  - 对特定公司感兴趣

### 3. **Pentest as a Service (PTaaS)** 🔍
- **描述：** 针对性、有时限的渗透测试项目
- **特点：** 明确的测试范围和期限
- **付费：** 通常固定费用 + 发现漏洞奖励
- **适合：**
  - 有完整测试方法论
  - 需要短期高收入
  - 团队合作能力

### 4. **Campaign / Challenge** 🎪
- **描述：** 限时活动，赏金加倍或特殊奖励
- **例子：**
  - Robinhood Campaign: 赏金 ×2，最高 $50k（14天）
  - Superhuman: 赏金 ×1.5，最高 $150k（30天）
- **适合：**
  - 时间充裕
  - 想要短期冲刺高收入

### 5. **AI Red Teaming** 🤖
- **描述：** 测试 AI 系统安全、安全性和信任问题
- **新兴领域：** AI 漏洞报告在 2025 年增长 210%
- **适合：**
  - 了解机器学习和 AI
  - 对 prompt injection、model poisoning 等有研究

### 6. **Audit Competition** 🏆 (Web3)
- **描述：** 智能合约代码审计竞赛
- **平台：** Immunefi, Code4rena
- **特点：** 多个研究员竞争找出最多/最严重漏洞
- **适合：** 智能合约审计专家

---

## 📊 三、难度等级与要求

### 🟢 **入门级 (Low - Medium)**
**特征：**
- 赏金范围：$50 - $500
- 漏洞类型：
  - Information Disclosure（信息泄露）
  - CSRF（跨站请求伪造）
  - Open Redirect（开放重定向）
  - Missing Security Headers
  - Rate Limiting 缺失

**技能要求：**
- 基础 Web 安全知识
- 了解 OWASP Top 10
- 会使用 Burp Suite / OWASP ZAP
- 基础 HTTP/HTTPS 理解

**环境要求：**
- 浏览器 + 代理工具（Burp Suite Community Edition 免费）
- 基础 Linux 环境（可用虚拟机）
- 网络连接

**时间成本：** 2-10 小时/漏洞

---

### 🟡 **中级 (Medium - High)**
**特征：**
- 赏金范围：$500 - $5,000
- 漏洞类型：
  - SQL Injection（SQL 注入）
  - XSS (Stored/Reflected)
  - Authentication Bypass（认证绕过）
  - Authorization Issues（权限问题）
  - Business Logic Flaws（业务逻辑漏洞）
  - SSRF（服务端请求伪造）

**技能要求：**
- 深入理解 Web 应用架构
- 熟悉常见框架（Django, Flask, React, Node.js）
- 能够读懂代码（JavaScript, Python, PHP）
- 了解 API 安全（REST, GraphQL）
- 会写 PoC (Proof of Concept)

**环境要求：**
- Burp Suite Professional (约 $400/年，推荐)
- Kali Linux 或同等渗透测试发行版
- Docker（用于复现漏洞环境）
- 本地开发环境（Node, Python, 数据库）

**时间成本：** 10-40 小时/漏洞

---

### 🔴 **高级 (High - Critical)**
**特征：**
- 赏金范围：$5,000 - $50,000+
- 漏洞类型：
  - RCE (Remote Code Execution)（远程代码执行）
  - Privilege Escalation（权限提升）
  - Account Takeover（账号接管）
  - Deserialization Attacks
  - Zero-Day Exploits
  - Advanced Business Logic Exploits
  - Smart Contract Vulnerabilities (Web3)

**技能要求：**
- 深入系统安全知识（OS, 网络协议）
- 逆向工程能力
  - IDA Pro / Ghidra
- Exploit 开发经验
- 源码审计能力
- 对目标技术栈深入理解

**环境要求：**
- 专业工具套件：
  - Burp Suite Professional
  - IDA Pro / Ghidra（逆向）
  - Metasploit Framework
  - Custom 脚本和工具
- 高性能测试环境：
  - 多核 CPU
  - 16GB+ RAM
  - SSD 存储
  - 虚拟化环境（VMware / VirtualBox）
- 网络实验室（如果测试 IoT/硬件）

**时间成本：** 40-200+ 小时/漏洞

---

### 💎 **专家级 (Critical - Exceptional)**
**特征：**
- 赏金范围：$50,000 - $200,000+
- 漏洞类型：
  - 0-day RCE in Critical Infrastructure
  - Full Chain Exploits（组合多个漏洞）
  - Smart Contract Exploits (DeFi)
  - Authentication System Bypass（完整认证系统绕过）
  - Kernel Exploits（内核漏洞）

**技能要求：**
- 顶尖安全研究员水平
- 能够发现和利用复杂漏洞链
- 深入的低级编程知识（C, Assembly）
- 创新研究能力

**环境要求：**
- 专业安全研究实验室
- 高端硬件（如需测试硬件漏洞）
- 多种操作系统和设备
- 付费订阅多种安全工具

**时间成本：** 数周到数月

**实例：**
- Cosmos（区块链）: $4k - $200k
- Superhuman (Grammarly): 最高 $150k

---

## 💰 四、金额范围详细分析

### 按平台统计

| 平台 | 低端赏金 | 中端赏金 | 高端赏金 | 最高记录 |
|------|---------|---------|---------|---------|
| **HackerOne** | $50 | $500-$5,000 | $10,000-$50,000 | $200,000+ |
| **Bugcrowd** | $50 | $300-$3,000 | $5,000-$25,000 | $100,000+ |
| **Intigriti** | €50 | €500-€5,000 | €10,000-€40,000 | €100,000+ |
| **Immunefi** | $500 | $5,000-$25,000 | $50,000-$250,000 | $10,000,000+ |

### 按漏洞严重程度

| 严重程度 | 典型赏金范围 | 描述 |
|---------|-------------|------|
| **Low** | $50 - $200 | 信息泄露、小问题 |
| **Medium** | $200 - $1,000 | CSRF、XSS（反射型）|
| **High** | $1,000 - $5,000 | SQL Injection、认证绕过 |
| **Critical** | $5,000 - $50,000+ | RCE、账号接管、数据泄露 |
| **Exceptional** | $50,000+ | 完整系统妥协、0-day |

### 按资产类型

| 资产类型 | 项目数量 (HackerOne) | 平均赏金范围 |
|---------|---------------------|-------------|
| **Domain** | 462 | $100 - $10k |
| **Wildcard** | 267 | $200 - $15k |
| **Android App** | 216 | $50 - $5k |
| **iOS App** | 212 | $50 - $5k |
| **Source Code** | 123 | $500 - $25k |
| **API** | 19 | $200 - $10k |
| **Hardware** | 20 | $500 - $50k |

### 实际案例赏金

**从 HackerOne 平台观察到的活跃项目：**

| 公司 | 赏金范围 | 特别活动 |
|------|---------|---------|
| **Superbet** | $100 - $10k | - |
| **Robinhood** | 一般：？ | Campaign: 最高 $50k (×2) |
| **Playtika** | 一般：？ | Campaign: 最高 $10k (×2) |
| **Superhuman (Grammarly)** | 一般：？ | Campaign: 最高 $150k (×1.5) |
| **DoorDash** | $50 - $12k | - |
| **Wallet on Telegram** | $100 - $100k | - |
| **Cosmos** | $4k - $200k | - |
| **Syfe** | $50 - $1k | Private program |
| **Vercel Open Source** | $50 - $10k | - |
| **23andMe** | $100 - $5k | - |

---

## 🖥️ 五、本地环境复现要求

### 基础配置（入门必备）

**硬件：**
- CPU: Intel Core i5 / AMD Ryzen 5 或更高
- RAM: 8GB（推荐 16GB）
- 存储: 256GB SSD
- 网络: 稳定的宽带连接

**软件：**
```
操作系统：
  - 主机: macOS / Windows / Linux
  - 虚拟机: Kali Linux / Parrot OS

浏览器工具：
  - Chrome / Firefox + Developer Tools
  - Extensions: FoxyProxy, Wappalyzer, EditThisCookie

代理工具：
  - Burp Suite Community Edition (免费)
  - OWASP ZAP (免费开源)

基础工具：
  - cURL / Postman (API 测试)
  - SQLMap (SQL injection)
  - Nikto (Web scanner)
  - Nmap (端口扫描)
```

**学习资源：**
- PortSwigger Web Security Academy (免费)
- OWASP Testing Guide
- HackerOne Hacker101 (免费课程)

**成本：** $0 - $50（免费工具足够入门）

---

### 中级配置（进阶研究）

**硬件升级：**
- CPU: Intel Core i7 / AMD Ryzen 7
- RAM: 16GB - 32GB
- 存储: 512GB SSD + 1TB HDD（存储漏洞测试环境和数据）
- 虚拟化: 支持 VT-x/AMD-V

**专业工具：**
```
付费工具：
  - Burp Suite Professional ($449/年)
    * Burp Scanner (自动漏洞扫描)
    * Burp Intruder (暴力测试)
    * Burp Collaborator (OOB 检测)
  
容器化环境：
  - Docker Desktop
  - docker-compose
  - DVWA, WebGoat (练习环境)

开发环境：
  - Node.js / npm
  - Python 3.x + pip
  - Git / GitHub
  - VS Code / Sublime Text

数据库：
  - MySQL / PostgreSQL
  - MongoDB
  - Redis
```

**网络实验室：**
- 路由器（用于测试网络攻击）
- 旧设备（测试 IoT 漏洞）

**成本：** $500 - $1,500/年

---

### 高级配置（专业级）

**硬件：**
- CPU: Intel Core i9 / AMD Ryzen 9 / M2 Pro/Max
- RAM: 32GB - 64GB
- 存储: 1TB NVMe SSD + 多个 HDD（测试环境隔离）
- GPU: 用于密码破解（如 Hashcat）
- 多显示器设置

**专业工具套件：**
```
逆向工程：
  - IDA Pro ($1,879 起)
  - Ghidra (NSA 免费工具)
  - x64dbg / OllyDbg
  
移动安全：
  - Frida (动态分析)
  - Objection
  - MobSF (Mobile Security Framework)
  - Android Studio + Genymotion
  - Xcode + iOS Simulator
  
智能合约 (Web3)：
  - Hardhat / Foundry
  - Slither (静态分析)
  - Mythril (安全分析)
  - Echidna (fuzzing)
  
网络安全：
  - Wireshark
  - Metasploit Framework Pro
  - Nessus Professional ($4,000+/年)
  - Cobalt Strike ($5,900/年)
```

**云环境：**
- AWS / Google Cloud / Azure（用于复现云环境漏洞）
- 预算: $100 - $500/月

**物理设备：**
- 各种移动设备（iPhone, Android）
- IoT 设备（如智能家居设备）
- Hardware hacking 工具（Raspberry Pi, Arduino, USB Rubber Ducky）

**成本：** $5,000 - $15,000 初期 + $2,000 - $5,000/年运营

---

### 专家级配置

**专业实验室：**
- 多台专用服务器
- 硬件安全分析设备（如 ChipWhisperer）
- 专业网络设备（交换机、防火墙、IDS/IPS）
- Faraday Cage（法拉第笼，RF 测试）

**特殊工具：**
- 软件无线电 (SDR)
- JTAG / UART 调试器
- Logic Analyzer（逻辑分析仪）
- Professional fuzzing 工具
- Zero-day exploit frameworks

**成本：** $20,000 - $100,000+

---

## 📈 六、收入潜力与难度对比

### 时间 vs 收入矩阵

| 投入时间/周 | 技能水平 | 月收入潜力 (USD) | 适合人群 |
|-----------|---------|----------------|---------|
| 5-10 小时 | 入门 | $100 - $500 | 学生、兼职 |
| 10-20 小时 | 中级 | $500 - $3,000 | 进阶研究员 |
| 20-40 小时 | 高级 | $3,000 - $15,000 | 专业 Bug Hunter |
| 40+ 小时 | 专家 | $15,000 - $100,000+ | 全职安全研究员 |

### 不同领域的竞争程度

| 领域 | 竞争程度 | 赏金水平 | 入门难度 |
|-----|---------|---------|---------|
| **Web 应用** | 🔴 激烈 | 💰 中等 | ⭐⭐ 中等 |
| **移动应用** | 🟡 中等 | 💰 中等 | ⭐⭐⭐ 中高 |
| **API 安全** | 🟡 中等 | 💰 中高 | ⭐⭐ 中等 |
| **智能合约 (Web3)** | 🟢 较低 | 💰💰 高 | ⭐⭐⭐⭐ 高 |
| **IoT / 硬件** | 🟢 低 | 💰💰 高 | ⭐⭐⭐⭐⭐ 很高 |
| **AI/ML 安全** | 🟢 很低 | 💰💰 高 | ⭐⭐⭐⭐ 高 |
| **云基础设施** | 🟡 中等 | 💰💰 高 | ⭐⭐⭐⭐ 高 |

**建议：**
- **新手：** 从 Web 应用开始，竞争虽激烈但学习资源多
- **有编程背景：** 考虑 API 安全或智能合约
- **想要高收入：** Web3/IoT 竞争较少但需深入技术
- **AI 背景：** AI/ML 安全是新兴蓝海

---

## 🎓 七、入门建议

### 第一步：建立基础
1. **完成免费课程：**
   - HackerOne Hacker101
   - PortSwigger Web Security Academy
   - OWASP Top 10 学习

2. **搭建练习环境：**
   - DVWA (Damn Vulnerable Web Application)
   - WebGoat
   - HackTheBox / TryHackMe

3. **了解法律和规则：**
   - 只测试授权目标
   - 遵守 Safe Harbor 政策
   - 不要破坏服务

### 第二步：选择平台
1. **注册账号：** HackerOne 或 Bugcrowd
2. **完成个人资料：** 展示你的技能和背景
3. **先从 VDP 开始：** 无经济压力，积累经验

### 第三步：找到第一个漏洞
1. **选择目标：**
   - 开始选择范围小的项目
   - 选择你熟悉的技术栈
   - 查看已披露的报告学习

2. **系统化测试：**
   - 遵循测试 checklist
   - 记录测试步骤
   - 不要遗漏基础测试

3. **撰写高质量报告：**
   - 清晰的标题和描述
   - 详细的复现步骤
   - PoC 截图/视频
   - 影响评估

### 第四步：持续进步
1. **阅读其他研究员的报告** (Disclosed reports)
2. **加入社区：** Twitter #bugbounty, Discord, Reddit
3. **分享你的发现：** 写博客、做演讲
4. **专注某个领域：** 成为某个领域的专家

---

## ⚠️ 八、注意事项与风险

### 法律风险
- ❌ **绝对不要：** 测试未授权的目标
- ❌ **绝对不要：** 超出测试范围
- ❌ **绝对不要：** 访问他人数据（即使你能）
- ✅ **务必：** 阅读并遵守 Safe Harbor / Rules of Engagement

### 经济风险
- **不稳定收入：** 初期可能数月无收入
- **时间成本：** 可能投入大量时间却找不到漏洞
- **竞争激烈：** 热门项目可能有数百人同时测试

### 技术风险
- **工具误用：** 可能导致服务中断（DDoS）
- **环境污染：** 测试环境可能感染恶意软件
- **隐私泄露：** 不当处理可能泄露测试数据

### 心理压力
- **Duplicate 报告：** 你发现的漏洞可能已被他人提交
- **报告被拒：** Not Applicable / Informative / Duplicate
- **Triage 延迟：** 可能数周才得到响应

---

## 📚 九、学习资源推荐

### 免费资源
- **PortSwigger Web Security Academy** (必学)
- **HackerOne Hacker101** + Hacker101 CTF
- **OWASP Top 10 + Testing Guide**
- **PentesterLab** (部分免费)
- **YouTube:** STÖK, LiveOverflow, InsiderPhD, NahamSec

### 付费课程
- **PentesterLab Pro** ($20/月)
- **BugBountyHunter** ($497一次性)
- **Web Security Academy Pro** ($99/年)

### 书籍
- *The Web Application Hacker's Handbook* - Dafydd Stuttard
- *Real-World Bug Hunting* - Peter Yaworski
- *Bug Bounty Bootcamp* - Vickie Li

### 社区
- **Twitter/X:** #bugbounty, #bugbountytips
- **Discord:** Bug Bounty Forum, NahamSec Discord
- **Reddit:** r/bugbounty

---

## 📊 十、总结与建议

### ✅ 优势
- **按效果付费：** 只为有效漏洞付费
- **灵活时间：** 可兼职或全职
- **无需学历：** 看能力不看文凭
- **全球化：** 在家工作，全球客户
- **高收入潜力：** 顶尖研究员年入数十万美元

### ❌ 挑战
- **初期困难：** 需要大量学习和练习
- **收入不稳定：** 尤其是初期
- **需要持续学习：** 技术快速变化
- **心理压力：** 竞争激烈，挫折感强

### 🎯 适合谁？
- ✅ **有技术背景：** 开发、运维、安全
- ✅ **好奇心强：** 喜欢探索和研究
- ✅ **耐心和毅力：** 能接受失败和长期投入
- ✅ **自学能力：** 主动学习新技术

### 💡 最终建议

**新手路线：**
```
1. 学习基础（2-3 个月）
   ↓
2. 练习环境（DVWA, HackTheBox）
   ↓
3. 参与 VDP（3-6 个月）
   ↓
4. 找到第一个有效漏洞
   ↓
5. 进入付费 BBP
   ↓
6. 专精某个领域
   ↓
7. 成为专业 Bug Hunter
```

**时间线预期：**
- **第 1-3 个月：** 学习基础，零收入
- **第 3-6 个月：** 找到第一个漏洞，$50-$500
- **第 6-12 个月：** 稳定找到漏洞，$500-$2,000/月
- **1-2 年后：** 专业水平，$2,000-$10,000/月
- **2+ 年：** 专家级，$10,000+/月

**初期投资建议：**
- **最低配置：** $0（使用免费工具）
- **推荐配置：** $500-$1,000（Burp Pro + 学习资源 + 基础硬件）
- **理想配置：** $2,000-$5,000（专业工具 + 高性能设备）

---

## 📞 十一、快速参考

### 推荐起步平台（新手）
1. **HackerOne** - 最大平台，资源最多
2. **Bugcrowd** - 专业支持好
3. **Intigriti** - 欧洲友好，社区活跃

### 推荐资产类型（新手）
1. **Domain / Web App** - 学习资源最多
2. **API** - 技术门槛适中，竞争较少
3. **Android App** - 工具成熟

### 避坑指南
- ❌ 不要一开始就挑战高难度目标（如 Google, Facebook）
- ❌ 不要忽视基础漏洞（Low 也是钱）
- ❌ 不要盲目使用自动化扫描器
- ❌ 不要跳过 reconnaissance 阶段
- ✅ 先质量后数量
- ✅ 详细记录测试过程
- ✅ 学习已披露报告

---

## 🔗 附录：重要链接

### 主要平台
- HackerOne: https://hackerone.com/
- Bugcrowd: https://www.bugcrowd.com/
- Intigriti: https://www.intigriti.com/
- YesWeHack: https://www.yeswehack.com/
- Immunefi (Web3): https://immunefi.com/

### 学习资源
- PortSwigger Academy: https://portswigger.net/web-security
- Hacker101: https://www.hacker101.com/
- OWASP: https://owasp.org/
- HackTheBox: https://www.hackthebox.com/
- TryHackMe: https://tryhackme.com/

### 工具
- Burp Suite: https://portswigger.net/burp
- OWASP ZAP: https://www.zaproxy.org/
- SQLMap: https://sqlmap.org/

### 社区
- Bug Bounty Forum: https://bugbountyforum.com/
- Reddit r/bugbounty: https://reddit.com/r/bugbounty

---

**报告结束**

如有任何问题或需要更详细的某个部分，请随时告知！🦞🎩
