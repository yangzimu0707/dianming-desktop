<!-- 这是 GitHub 仓库 yangzimu0707/dianming-desktop 的 README.md 内容，直接整份复制/上传即可 -->

# Class Roll Call · 班级点名大师

> A Windows desktop toolkit for the classroom.
> 为课堂准备的 Windows 桌面小工具。

Roll call · random grouping · AI chat · reaction & short-term-memory training

---

## Download

### ✅ Recommended: Microsoft Store

Search **班级点名大师** on the Microsoft Store.

Signed and distributed by Microsoft — no security warnings during installation, and updates are handled automatically.

### Or: download the EXE directly

👉 **[Download the latest version](https://github.com/yangzimu0707/dianming-desktop/releases/latest)**

The installer file is named `ClassRollCall-Setup-x.y.z.exe`.

---

## ⚠️ About security warnings when installing (please read first)

This app is **not signed with a trusted commercial code-signing certificate**, so your system may block it.

**Depending on your system there are two different blocks, and whether you can click through differs completely.** Figure out which one you have first.

### First: SmartScreen (most people, you can click through)

When you run an installer downloaded from a browser, Windows shows a blue prompt:

**"Windows protected your PC"**

This is how Windows treats **every program that is unsigned (or signed by an untrusted certificate) and not yet widely downloaded**. It does **not** mean the file is unsafe. To install:

1. Click **"More info"** in the prompt
2. Click **"Run anyway"** that appears below
3. Continue with the normal installation

> You only face this prompt once. There is no built-in auto-update, so later versions are also downloaded manually.

### Second: Smart App Control (some Windows 11 devices, **no way through**)

If your Windows 11 was **cleanly installed** (not upgraded from an older version), Smart App Control may be enabled. It blocks unsigned programs outright, and **there is no "Run anyway" option**:

- The message looks like "Smart App Control blocked this app"
- **There is no per-app exception** — the feature simply does not work that way, and there is no allow list
- The only way around it is to turn Smart App Control off entirely — and once off, it **can only be re-enabled by resetting or reinstalling Windows**

**How to turn it off:** open **Windows Security → App & browser control → Smart App Control** and set it to **Off**.

**Once it is off, it can only be turned back on by resetting or reinstalling Windows** — so decide before you do it. If you would rather not, just use the Microsoft Store version above instead: Store apps are signed and distributed by Microsoft and are treated as trusted, so they are not affected.

### Which one are you seeing?

| What you see | Which block | What to do |
|---|---|---|
| Blue "Windows protected your PC" with a clickable "More info" | SmartScreen | Click "More info" → "Run anyway" |
| "Smart App Control blocked this app" with **no button to proceed** | Smart App Control | Turn it off in Windows Security (see above), or use the Microsoft Store version |

---

## Features

**🎲 Random roll call** — draw names in one click, with options for no-repeat and how many to draw. History and stats are kept automatically.

**👥 Random grouping** — split the class by number of groups or by group size.

**🧠 AI chat room** — requires your own API key (any DeepSeek / Qwen-compatible endpoint) or a local Ollama install. Not included out of the box.

**⚡ Reaction-time test** — a small reflex game.

**🎯 Short-term memory** — a memory-span training game.

**🎂 Birthday reminders** — you only fill in month and day; the app reminds you on the day.

**🎨 New interface** — a left sidebar that collapses into a frosted, see-through drawer.

---

## Privacy

**Your class data stays on your machine. Nothing is uploaded to any server.**

- No account required
- The roster, groups, roll-call history and settings are stored locally, next to the app (on the same drive, e.g. `D:\DianMing桌面数据`)
- The AI chat room is opt-in and needs your own configuration: whatever you type is sent to the service **you** configured (for example, your own DeepSeek API key). This app does not relay or store it. If you use local Ollama, nothing leaves your computer at all
- Full privacy policy: https://yzmdwz.com/privacy.html

---

## Requirements

- Windows 10 / 11 (64-bit)

---

## Feedback

Found a bug or have a feature request? Please open an issue:

https://github.com/yangzimu0707/dianming-desktop/issues

---
---

# 班级点名大师 · Class Roll Call

> 为课堂准备的 Windows 桌面小工具。

课堂点名 · 随机分组 · AI 聊天室 · 反射弧与短时记忆训练

---

## 下载

### ✅ 推荐：微软商店

在微软商店搜索 **班级点名大师**。

由微软签名和分发，安装时不弹任何安全提示，后续更新也由商店自动完成。

### 或者：直接下载 EXE

👉 **[下载最新版](https://github.com/yangzimu0707/dianming-desktop/releases/latest)**

安装包文件名是 `ClassRollCall-Setup-x.y.z.exe`。

---

## ⚠️ 安装时的安全提示（请先看一眼）

本应用**没有使用受信任的商业代码签名证书**，所以安装时可能被系统拦下。

**根据你的系统情况有两道拦截，能不能点过去完全不同** —— 请先分清自己是哪一种。

### 第一道：SmartScreen（大部分人遇到，可以点过去）

从浏览器下载的安装包首次运行时，Windows 会弹出蓝色提示：

**「Windows 已保护你的电脑」**（英文系统为 *Windows protected your PC*）

这是 Windows 对**所有「没有可信签名、下载量还不高」的程序**的统一处理方式，**不代表文件有问题**。安装时这样做：

1. 点击提示框里的 **「更多信息」**
2. 点击随后出现的 **「仍要运行」**
3. 正常走安装流程即可

> 这个提示你只需要面对一次。本应用没有内置自动更新，后续版本同样是自己下载安装。

### 第二道：智能应用控制（部分 Windows 11 遇到，**点不过去**）

如果你用的是**全新安装的** Windows 11（不是从旧系统升级上来的），系统可能开着「智能应用控制」（Smart App Control）。它会直接拦下未签名的程序，而且**没有「仍要运行」这个选项**：

- 提示内容类似「智能应用控制已阻止此应用」
- **不支持针对单个应用放行** —— 系统层面就没有这个功能，也没有例外名单
- 唯一的办法是把「智能应用控制」整个关掉，但它**一旦关闭，必须重置或重装 Windows 才能再打开**

**关闭方法**：打开 **Windows 安全中心 → 应用和浏览器控制 → 智能应用控制**，把它设为**关闭**。

**注意：一旦关闭，只有重置或重装 Windows 才能重新打开** —— 决定前请想清楚。不想关闭的话，直接用上面的微软商店版本即可：商店里的应用由微软签名和分发、被系统视为可信，不受这道限制影响。

### 怎么判断自己遇到的是哪一道

| 你看到的 | 是哪一道 | 怎么办 |
|---|---|---|
| 蓝底「Windows 已保护你的电脑」，有「更多信息」可点 | SmartScreen | 点「更多信息」→「仍要运行」 |
| 「智能应用控制已阻止此应用」，**没有任何可以点过去的按钮** | 智能应用控制 | 在安全中心关闭它（见上文），或改用微软商店版本 |

---

## 功能

**🎲 随机点名** —— 一键抽人，可选不重复、可选抽取人数；点名历史与统计自动留存。

**👥 随机分组** —— 按组数或每组人数随机分组。

**🧠 AI 聊天室** —— 需要自行配置 API Key（任何兼容 DeepSeek / Qwen 的接口）或使用本地 Ollama，不预置云端额度。

**⚡ 反射弧测试** —— 反应速度小游戏。

**🎯 短时记忆** —— 记忆广度训练。

**🎂 生日提醒** —— 只需填写月和日，生日当天自动提醒。

**🎨 全新界面** —— 左侧导航栏，可收起为抽屉，带磨砂透视效果。

---

## 隐私

**班级数据只存在你自己的电脑上，不会上传到任何服务器。**

- 不需要注册账号
- 名单、分组、点名历史和设置都保存在本机（与程序同一个磁盘，例如 `D:\DianMing桌面数据`）
- AI 聊天室属于需要自行配置的功能：你输入的内容只会发送到**你自己配置的那个服务**（例如你填的 DeepSeek API Key），本应用不中转、不保存。如果改用本地 Ollama，全部推理都在你电脑上完成，不联网
- 隐私政策全文：https://yzmdwz.com/privacy.html

---

## 系统要求

- Windows 10 / 11（64 位）

---

## 问题反馈

遇到问题或有功能建议，欢迎在这里提 Issue：

https://github.com/yangzimu0707/dianming-desktop/issues
