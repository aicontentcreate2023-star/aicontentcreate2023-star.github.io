# Bug Bounty 待选题目列表

📄 **创建时间：** 2026-03-01 20:03 GMT+8  
🎯 **目的：** 摸底练习，建立协作流程  
✅ **标准：** 环境可本地复制 + 有源码 + 可埋log分析

---

## 📋 待选列表（按推荐顺序）

### 🥇 第一候选：Rich（Python 终端渲染库）⭐ 开始这个！

**项目信息：**
- **Repo：** https://github.com/Textualize/rich
- **Issues：** https://github.com/Textualize/rich/issues?q=is:open+label:bug
- **语言：** Python
- **类型：** 终端输出渲染 bug

**环境搭建：**
```bash
git clone https://github.com/Textualize/rich.git
cd rich
pip install -e .
```

**优点：**
- ✅ 环境超简单（一行 pip）
- ✅ 代码清晰易读
- ✅ 很多 good first issues
- ✅ 渲染问题容易复现
- ✅ 可以添加 print() 调试

**难度：** 低  
**预估时间：** 1-3 天  
**赏金预期：** $0-$200（练手为主）

---

### 🥈 第二候选：Click（Python CLI 框架）

**项目信息：**
- **Repo：** https://github.com/pallets/click
- **Issues：** https://github.com/pallets/click/issues?q=is:open+label:bug
- **语言：** Python
- **类型：** CLI 参数解析、命令处理

**环境搭建：**
```bash
git clone https://github.com/pallets/click.git
cd click
pip install -e .
```

**优点：**
- ✅ 广泛使用（Flask 团队维护）
- ✅ 代码质量高
- ✅ 测试覆盖好
- ✅ 文档完善

**难度：** 低-中  
**预估时间：** 2-5 天

---

### 🥉 第三候选：Typer（现代 Python CLI 框架）

**项目信息：**
- **Repo：** https://github.com/fastapi/typer
- **Issues：** https://github.com/fastapi/typer/issues?q=is:open+label:bug
- **语言：** Python（基于 Click）
- **类型：** Type hints CLI 框架

**环境搭建：**
```bash
git clone https://github.com/fastapi/typer.git
cd typer
pip install -e .
```

**优点：**
- ✅ FastAPI 作者维护
- ✅ 现代 Python 特性
- ✅ 社区活跃

**难度：** 中  
**预估时间：** 2-5 天

---

### 4. Chalk（JavaScript 终端颜色）

**项目信息：**
- **Repo：** https://github.com/chalk/chalk
- **Issues：** https://github.com/chalk/chalk/issues?q=is:open+label:bug
- **语言：** JavaScript
- **类型：** 终端颜色处理

**环境搭建：**
```bash
git clone https://github.com/chalk/chalk.git
cd chalk
npm install
```

**优点：**
- ✅ 超级流行（100M+ 下载/月）
- ✅ 代码简洁
- ✅ 问题通常很具体

**难度：** 低  
**适合：** 熟悉 JavaScript

---

### 5. Commander.js（JavaScript CLI 框架）

**项目信息：**
- **Repo：** https://github.com/tj/commander.js
- **Issues：** https://github.com/tj/commander.js/issues?q=is:open+label:bug
- **语言：** JavaScript/TypeScript
- **类型：** CLI 参数解析

**环境搭建：**
```bash
git clone https://github.com/tj/commander.js.git
cd commander.js
npm install
```

**优点：**
- ✅ Node.js 生态标准
- ✅ 测试完善
- ✅ 维护活跃

**难度：** 低-中  
**适合：** 熟悉 Node.js

---

### 6. Inquirer.js（交互式命令行）

**项目信息：**
- **Repo：** https://github.com/SBoudrias/Inquirer.js
- **Issues：** https://github.com/SBoudrias/Inquirer.js/issues?q=is:open+label:bug
- **语言：** JavaScript
- **类型：** 命令行交互、提示

**环境搭建：**
```bash
git clone https://github.com/SBoudrias/Inquirer.js.git
cd Inquirer.js
npm install
```

**优点：**
- ✅ 用户交互问题容易复现
- ✅ 可视化效果明显

**难度：** 中  
**适合：** 喜欢 UI 相关

---

### 7. Cobra（Go CLI 框架）

**项目信息：**
- **Repo：** https://github.com/spf13/cobra
- **Issues：** https://github.com/spf13/cobra/issues?q=is:open+label:bug
- **语言：** Go
- **类型：** CLI 框架

**环境搭建：**
```bash
git clone https://github.com/spf13/cobra.git
cd cobra
go mod download
```

**优点：**
- ✅ Kubernetes、Docker 等都用它
- ✅ Go 代码简洁
- ✅ 编译型语言经验

**难度：** 低-中  
**适合：** 想学 Go

---

### 8. Viper（Go 配置管理）

**项目信息：**
- **Repo：** https://github.com/spf13/viper
- **Issues：** https://github.com/spf13/viper/issues?q=is:open+label:bug
- **语言：** Go
- **类型：** 配置文件、环境变量处理

**环境搭建：**
```bash
git clone https://github.com/spf13/viper.git
cd viper
go mod download
```

**优点：**
- ✅ 配置管理标准库
- ✅ 测试完善

**难度：** 中  
**适合：** 熟悉配置系统

---

## 🎯 当前行动：第一候选 Rich

**老大已决定：先从第一个开始**

### Rich 项目 - 立即行动计划

**Step 1: 选择具体 issue（需要做）**
- 访问：https://github.com/Textualize/rich/issues?q=is:open+label:bug
- 筛选标准：
  - ✅ 有清晰的复现步骤
  - ✅ 有代码示例
  - ✅ 最近更新（< 3个月）
  - ✅ 没有太多人在做

**Step 2: 环境搭建（5分钟）**
```bash
git clone https://github.com/Textualize/rich.git
cd rich
pip install -e .
```

**Step 3: 复现 bug（10-30分钟）**
- 按照 issue 描述复现
- 添加 debug 输出
- 确认问题存在

**Step 4: 分析 root cause（1-4小时）**
- 阅读相关代码
- 追踪执行流程
- 找到问题根源

**Step 5: 提出修复方案**
- 写修复代码
- 运行测试
- 准备 PR

---

## 🚀 执行状态

**当前任务：** Rich（第一候选）  
**状态：** 等待选择具体 issue  
**负责人：** 一号 + 四号  

**下一步：**
老大从 Rich issues 中选一个，或让我们推荐一个

---

## 📊 预期时间线

**Day 1:**
- 选定具体 issue
- 环境搭建
- 复现 bug
- 初步分析

**Day 2-3:**
- 深入分析
- 写修复
- 测试验证

**Day 4:**
- 提交 PR
- 响应 review

---

**待命中，等待老大选择具体 Rich issue！** 🦞🤖
