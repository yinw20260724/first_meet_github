# 初识 GitHub

> 2026 年 7 月 26 日 · 新电脑上的第一天

今天在新电脑上完成了几件和 GitHub 有关的小事，记录一下。

## 一、GitHub 汉化（Google 浏览器）

新电脑装好 Google 浏览器后，给 GitHub 装上了中文汉化插件，界面看起来亲切多了。

## 二、关注了我老公

在 GitHub 上关注了我老公的账号，以后可以随时看到他的动态和项目更新。

## 三、Codex 连接 GitHub MCP

给 Codex 装上了「GitHub 账号的手和眼」，这样 Codex 就能直接帮我操作 GitHub 了——建仓库、提交代码、管理 Issue，都不用离开对话窗口。

### 连接步骤

1. 打开 [GitHub Settings / Tokens](https://github.com/settings/tokens)，新增一个 Personal Access Token（令牌）
2. 在终端运行以下命令，把令牌设置为环境变量：

   ```powershell
   setx GITHUB_TOKEN "ghp_你的令牌"
   ```

3. 重启终端，Codex 就能通过 GitHub MCP 读取和操作你的 GitHub 账号了

---

第一天，一切刚开始。🌱
