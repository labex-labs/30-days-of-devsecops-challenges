# DevSecOps 30 天挑战

**支持语言:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/zh/courses/30-days-of-devsecops-challenges">
    <img src="https://course-cover.labex.io/30-days-of-devsecops-challenges.png?lang=zh" alt="DevSecOps 30 天挑战">
  </a>
</p>

一条从 DevSecOps Linux 与 Docker 安全实验中精选的 30 天挑战路线，从主机暴露面审计逐步进阶到权限、密钥、服务身份、容器加固、Compose 隔离、镜像治理和事件清理。

[在 LabEx 开始课程](https://labex.io/zh/courses/30-days-of-devsecops-challenges)

## 练习

|   序号 | 名称                     | 难度   | 练习                                                                                                                                                    |
|------|------------------------|------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
|   01 | 审计监听服务                 | 初级   | <a target='_blank' href='https://labex.io/zh/labs/linux-audit-listening-services-662167?course=30-days-of-devsecops-challenges'>开始挑战</a>              |
|   02 | 移除不必要的公共端口             | 初级   | <a target='_blank' href='https://labex.io/zh/labs/linux-remove-unnecessary-public-port-662316?course=30-days-of-devsecops-challenges'>开始挑战</a>        |
|   03 | 将管理界面限制在本地主机           | 初级   | <a target='_blank' href='https://labex.io/zh/labs/linux-restrict-admin-interface-to-localhost-662317?course=30-days-of-devsecops-challenges'>开始挑战</a> |
|   04 | 禁用 Web 目录列表            | 初级   | <a target='_blank' href='https://labex.io/zh/labs/linux-disable-web-directory-listing-662309?course=30-days-of-devsecops-challenges'>开始挑战</a>         |
|   05 | 移除暴露的备份归档文件            | 初级   | <a target='_blank' href='https://labex.io/zh/labs/linux-remove-exposed-backup-archive-662313?course=30-days-of-devsecops-challenges'>开始挑战</a>         |
|   06 | 修复不安全的密钥文件权限           | 初级   | <a target='_blank' href='https://labex.io/zh/labs/linux-fix-unsafe-secret-file-permissions-662310?course=30-days-of-devsecops-challenges'>开始挑战</a>    |
|   07 | 修复全局可写的 Web 目录         | 初级   | <a target='_blank' href='https://labex.io/zh/labs/linux-fix-world-writable-web-directory-662311?course=30-days-of-devsecops-challenges'>开始挑战</a>      |
|   08 | 专用服务用户                 | 中级   | <a target='_blank' href='https://labex.io/zh/labs/dedicated-service-user-662278?course=30-days-of-devsecops-challenges'>开始挑战</a>                      |
|   09 | 服务环境变量文件               | 中级   | <a target='_blank' href='https://labex.io/zh/labs/service-env-file-662284?course=30-days-of-devsecops-challenges'>开始挑战</a>                            |
|   10 | 日志写入边界                 | 中级   | <a target='_blank' href='https://labex.io/zh/labs/log-write-boundary-662281?course=30-days-of-devsecops-challenges'>开始挑战</a>                          |
|   11 | 移除硬编码凭据                | 中级   | <a target='_blank' href='https://labex.io/zh/labs/linux-remove-hardcoded-credentials-662314?course=30-days-of-devsecops-challenges'>开始挑战</a>          |
|   12 | 处理进程环境变量中的密钥           | 中级   | <a target='_blank' href='https://labex.io/zh/labs/process-env-secret-662282?course=30-days-of-devsecops-challenges'>开始挑战</a>                          |
|   13 | 移除权限过大的 Sudo 规则        | 中级   | <a target='_blank' href='https://labex.io/zh/labs/linux-remove-over-permissive-sudo-rule-662315?course=30-days-of-devsecops-challenges'>开始挑战</a>      |
|   14 | 安全的脚本 PATH             | 中级   | <a target='_blank' href='https://labex.io/zh/labs/safe-script-path-662283?course=30-days-of-devsecops-challenges'>开始挑战</a>                            |
|   15 | 加固以 root 权限运行的 Cron 任务 | 中级   | <a target='_blank' href='https://labex.io/zh/labs/linux-harden-root-run-cron-job-662312?course=30-days-of-devsecops-challenges'>开始挑战</a>              |
|   16 | Compose 移交审计           | 中级   | <a target='_blank' href='https://labex.io/zh/labs/compose-handoff-audit-662564?course=30-days-of-devsecops-challenges'>开始挑战</a>                       |
|   17 | 支持门户审计                 | 初级   | <a target='_blank' href='https://labex.io/zh/labs/support-portal-audit-662472?course=30-days-of-devsecops-challenges'>开始挑战</a>                        |
|   18 | 指标端点暴露                 | 初级   | <a target='_blank' href='https://labex.io/zh/labs/metrics-endpoint-exposure-662477?course=30-days-of-devsecops-challenges'>开始挑战</a>                   |
|   19 | 本地调试控制台                | 初级   | <a target='_blank' href='https://labex.io/zh/labs/local-debug-console-662476?course=30-days-of-devsecops-challenges'>开始挑战</a>                         |
|   20 | 内部数据库访问                | 中级   | <a target='_blank' href='https://labex.io/zh/labs/internal-database-access-662567?course=30-days-of-devsecops-challenges'>开始挑战</a>                    |
|   21 | 只读配置挂载                 | 中级   | <a target='_blank' href='https://labex.io/zh/labs/read-only-config-mount-662479?course=30-days-of-devsecops-challenges'>开始挑战</a>                      |
|   22 | 非 Root 权限镜像工作进程        | 中级   | <a target='_blank' href='https://labex.io/zh/labs/non-root-image-worker-662478?course=30-days-of-devsecops-challenges'>开始挑战</a>                       |
|   23 | 最小权限日志收集器              | 中级   | <a target='_blank' href='https://labex.io/zh/labs/least-privilege-log-collector-662475?course=30-days-of-devsecops-challenges'>开始挑战</a>               |
|   24 | Webhook Docker Socket  | 中级   | <a target='_blank' href='https://labex.io/zh/labs/webhook-docker-socket-662481?course=30-days-of-devsecops-challenges'>开始挑战</a>                       |
|   25 | 作用域受限的 Compose 密钥      | 中级   | <a target='_blank' href='https://labex.io/zh/labs/scoped-compose-secret-662569?course=30-days-of-devsecops-challenges'>开始挑战</a>                       |
|   26 | 拆分服务网络                 | 中级   | <a target='_blank' href='https://labex.io/zh/labs/split-service-networks-662571?course=30-days-of-devsecops-challenges'>开始挑战</a>                      |
|   27 | API Token in Env       | 中级   | <a target='_blank' href='https://labex.io/zh/labs/api-token-in-env-662473?course=30-days-of-devsecops-challenges'>开始挑战</a>                            |
|   28 | 构建令牌泄露                 | 中级   | <a target='_blank' href='https://labex.io/zh/labs/build-token-leak-662474?course=30-days-of-devsecops-challenges'>开始挑战</a>                            |
|   29 | 构建更安全的 Worker 镜像       | 中级   | <a target='_blank' href='https://labex.io/zh/labs/safer-worker-image-662480?course=30-days-of-devsecops-challenges'>开始挑战</a>                          |
|   30 | 事故调试清理                 | 高级   | <a target='_blank' href='https://labex.io/zh/labs/incident-debug-cleanup-662566?course=30-days-of-devsecops-challenges'>开始挑战</a>                      |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

