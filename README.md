<h1 align="center">天智工坊 · Tianmind Studio</h1>

<p align="center">
  <b>独立开发者工作室 · 全栈开发 · AI 应用 · SaaS 定制 · 可签合同开票</b><br/>
  <sub>Production-grade software for real business use — websites, admin systems, AI workflows, and self-hosted deployments.</sub>
</p>

<p align="center">
  <a href="https://tianmind.com"><img src="https://img.shields.io/badge/官网-tianmind.com-0A66C2?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"/></a>
  <a href="https://github.com/491034170/services"><img src="https://img.shields.io/badge/服务目录-Services-4FACFE?style=flat-square&logo=github&logoColor=white" alt="Services"/></a>
  <a href="https://github.com/491034170/site-bootstrap"><img src="https://img.shields.io/badge/旗舰-site--bootstrap-111111?style=flat-square&logo=github&logoColor=white" alt="site-bootstrap"/></a>
  <a href="https://491034170.github.io/tianmind-landing/"><img src="https://img.shields.io/badge/在线演示-Live_Demo-7C3AED?style=flat-square&logo=githubpages&logoColor=white" alt="Live Demo"/></a>
  <a href="mailto:wx@tianmind.com"><img src="https://img.shields.io/badge/Email-wx@tianmind.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/淘宝店-天智工坊-FF6A00?style=flat-square&logo=alibabadotcom&logoColor=white" alt="Taobao"/>
  <img src="https://img.shields.io/badge/营业执照-已认证-2EA043?style=flat-square&logo=shield&logoColor=white" alt="Licensed"/>
</p>

---

## 先看这里 / Start here

如果你是第一次来到这个 GitHub，建议从这两条路径之一入手：

### 🛠 建站 / 部署 工程工具链（最新开源）

真实业务里沉淀多年、今年起整理脱敏成开源工具的一条完整链路。适合拿到 VPS 想自建站点 / 做代码服务的同行：

1. ⭐ [**site-bootstrap**](https://github.com/491034170/site-bootstrap) · [Live Site](https://491034170.github.io/site-bootstrap/) · [Release](https://github.com/491034170/site-bootstrap/releases/latest) — 一条命令把静态站或 Node 应用部到你的 VPS。Cloudflare DNS + nginx + Let's Encrypt 全链路自动化，带 rollback 和 `--dry-run`。
2. ⭐ [**vps-init**](https://github.com/491034170/vps-init) · [Live Site](https://491034170.github.io/vps-init/) · [Release](https://github.com/491034170/vps-init/releases/latest) — 一键初始化 Ubuntu / Debian VPS。**为中国大陆 / 香港 VPS 做过针对性调优**：阿里云镜像、fail2ban bantime 升级、小内存 VPS 的 swap 策略、SSH 加固带防锁死保护。
3. ⭐ [**cloudflare-cn-kit**](https://github.com/491034170/cloudflare-cn-kit) · [Live Site](https://491034170.github.io/cloudflare-cn-kit/) · [Release](https://github.com/491034170/cloudflare-cn-kit/releases/latest) — 面向中国/香港运维的 CF CLI。**核心卖点**：一条命令诊断最常撞的 Flexible-SSL 无限重定向死循环。

### 📦 其它作品 / Other projects

4. [services](https://github.com/491034170/services) — 服务范围、起价、合作流程、FAQ
5. [word-pdf-watermark-macos](https://github.com/491034170/word-pdf-watermark-macos) · [Live Site](https://491034170.github.io/word-pdf-watermark-macos/) — 把本地 macOS 小工具整理成真正可下载、可维护、可验证的项目
6. [tianmind-landing](https://github.com/491034170/tianmind-landing) · [Live Demo](https://491034170.github.io/tianmind-landing/) — 工作室品牌落地页模板
7. [expert-review-panel](https://github.com/491034170/expert-review-panel) · [Live Guide](https://491034170.github.io/expert-review-panel/) — 严审型 Claude Skill / AI 工作流
8. [english-coach](https://github.com/491034170/english-coach) · [Live Guide](https://491034170.github.io/english-coach/) — 把日常对话变成英语训练

---

## 我是谁 / About

我是王鑫，运营 **天智工坊（Tianmind Studio）**。

我做的不是“看起来像 demo 的玩具项目”，而是面向真实使用场景的交付：
- 能上线的官网与落地页
- 能落地的后台 / SaaS / 内部工具
- 能接入业务流的 AI 功能与 Agent 工作流
- 能部署、能维护、能交付源码的完整工程

公开仓库主要承担两个角色：
- 展示我能做出什么
- 让潜在客户、合作者、贡献者快速判断我的工作方式

---

## 我做什么 / What I build

| 方向 | 典型交付 | 适合谁 |
|---|---|---|
| **企业官网 / 品牌落地页** | 双语站点、产品页、SEO 基础、Cloudflare / VPS 部署 | 独立开发者、小团队、工作室、内容创作者 |
| **后台 / 内部工具** | 管理系统、审批流、报表、权限系统、表单流程 | 中小企业、工作室、运营团队 |
| **SaaS 定制** | 多租户改造、企业版功能、数据看板、租户隔离 | 有长期业务流程的软件团队 |
| **AI 应用 / Agent** | Claude Skill、LLM 集成、Prompt 工程、内容生成、工作流自动化 | 想把 AI 真正接进业务的团队 |
| **部署与托管** | Docker、Nginx / Caddy、SSL、域名、Cloudflare、自动部署 | 不想自己折腾上线细节的客户 |

完整服务目录见：[services](https://github.com/491034170/services)

---

## 代表作 / Featured work

### 🛠 建站 / 部署 工程工具链

真实 production 场景沉淀的工具。每一个都带 CI、LICENSE、Release、CHANGELOG，跑过真实生产环境，然后整理脱敏后开源。

### 1) [site-bootstrap](https://github.com/491034170/site-bootstrap) ⭐
一条命令把静态站或 Node 应用部署到你自己的 VPS — 带 Cloudflare DNS + nginx + Let's Encrypt 全链路自动化。
- 子命令：`new` / `deploy` / `dns` / `cert` / `rollback` / `doctor`
- 每次部署自动快照上一版，`rollback` 一条命令切回去
- `--dry-run` 每一步都可预览
- 纯 Bash，依赖只有 ssh + rsync + jq + curl
- Latest Release：<https://github.com/491034170/site-bootstrap/releases/latest>

### 2) [vps-init](https://github.com/491034170/vps-init) ⭐
一键把全新的 Ubuntu / Debian VPS 初始化为生产环境 —— **为中国大陆 / 香港 VPS 做过实际踩出来的调优**。
- 4 种预设 profile：`minimal` / `web-cn` / `node-app` / `docker-host`
- 中国场景专属：aliyun/tuna/ustc/163/huaweicloud 镜像支持 + Ubuntu 24.04 deb822 格式兼容
- 安全工程细节：fail2ban `bantime.increment`、小内存 VPS 的 `vm.swappiness=10`、SSH 加固带**防锁死保护**（没放 key 的情况下不让关密码登录）
- 模块全部幂等，`--dry-run` 可预览
- Latest Release：<https://github.com/491034170/vps-init/releases/latest>

### 3) [cloudflare-cn-kit](https://github.com/491034170/cloudflare-cn-kit) ⭐
面向中国/香港运维的 Cloudflare CLI，核心卖点是诊断那个把无数人坑哭的 Flexible-SSL 无限重定向死循环。
- `cfcn ssl diag <domain>` 一条命令告诉你是否踩了 Flexible SSL 坑 + 如何修
- 批量 DNS 操作（YAML 驱动）+ 多租户泛解析一条命令
- 全程走 scoped API token，不要古老的 X-Auth-Key
- 和 `site-bootstrap` / `vps-init` 共享 `CF_API_TOKEN` 环境变量
- Latest Release：<https://github.com/491034170/cloudflare-cn-kit/releases/latest>

---

### 4) [word-pdf-watermark-macos](https://github.com/491034170/word-pdf-watermark-macos)
一个把桌面上的 macOS 文档工具，整理成真正像样开源项目的例子，也代表我做项目时的交付方式：不只交一个能跑的结果，而是把源码、说明、发布、验证和维护路径一起补齐。
- 有源码，不只是编译好的 `.app`
- 有 GitHub Pages 落地页 / 下载页
- 有 Release、SHA256、MIT License
- 有 macOS GitHub Actions smoke test
- 看源码：<https://github.com/491034170/word-pdf-watermark-macos>
- Live Site：<https://491034170.github.io/word-pdf-watermark-macos/>

### 5) [tianmind-landing](https://github.com/491034170/tianmind-landing)
工作室 / 独立开发者品牌落地页模板，零构建、零依赖，可直接部署到 GitHub Pages 或 Cloudflare Pages。
- 看源码：<https://github.com/491034170/tianmind-landing>
- 看演示：<https://491034170.github.io/tianmind-landing/>

### 6) [expert-review-panel](https://github.com/491034170/expert-review-panel)
严审型 Claude Skill：模拟多专家评审团，在论文、BP、代码、竞赛材料真正提交之前，先把致命问题翻出来。
- Live Guide：<https://491034170.github.io/expert-review-panel/>

### 7) [english-coach](https://github.com/491034170/english-coach)
把每一次 Claude 对话变成英语练习：先回答问题，再纠错，再教一个更自然的表达。
- Live Guide：<https://491034170.github.io/english-coach/>

### 8) 商业项目：ruoyi-saas（私有，可提供 demo）
基于 RuoYi-Vue 的多租户 SaaS 管理系统，支持企业租户隔离、泛域名部署、定制功能扩展。

---

## 为什么找我 / Why work with me

- **不是黑箱开发**：按里程碑给可运行 demo
- **不是只交页面**：源码、部署、说明文档一起交付
- **不是只会写 prompt**：前后端、部署、AI 集成都能落地
- **不是个人随便接单**：有营业执照，可签合同，可开票
- **不是做完就失联**：支持验收、修复、后续维护

---

## 合作入口 / Contact

- 🌐 官网：<https://tianmind.com>
- 📧 邮箱：<mailto:wx@tianmind.com>
- 🛒 淘宝：搜索「天智工坊」
- 💬 GitHub：在 [services](https://github.com/491034170/services/issues/new) 提交需求也可以

如果你想快速判断我适不适合你的项目，建议直接发这 4 条：
1. 你要做什么
2. 目标上线时间
3. 预算范围
4. 有没有参考案例

---

## 给访客的话 / For visitors

这个 GitHub 账号的重点，不是刷成就，也不是堆空仓库。

我更在意这里的内容能不能真的帮助别人：
- 对客户来说，能不能看懂我能交付什么
- 对开发者来说，能不能直接拿去参考、Fork、复用
- 对潜在合作方来说，能不能快速建立信任

如果这些仓库对你有帮助，欢迎点个 Star。

<p align="center">
  <sub>© 天智工坊 · Tianmind Studio · Build. Think. Transcend.</sub>
</p>
