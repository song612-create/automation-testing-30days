# Day 0 · 环境准备记录（2026-11-04）

## 已完成

- [x] Python 3.11.9 安装到 `D:\python`，已加入用户 PATH
- [x] pip 24.0 可用，已配置阿里云镜像（清华源当时返回 403）
- [x] Git 2.56.0 安装到 `D:\git`，已在机器 PATH
- [x] Git 全局身份：`song <1377958869@qq.com>`
- [x] Git 中文与换行相关配置：`init.defaultBranch=main`、`core.autocrlf=true`、`core.quotepath=false`、`i18n.*Encoding=utf-8`
- [x] 项目仓库初始化：`D:\projects\automation-testing-30days`

## 远程仓库

- GitHub 账号已注册（2026-11-04），作为主仓库（简历通用）
- Gitee 账号已有，作为国内镜像（推送快、不怕 GitHub 抽风）
- 约定：`origin` → GitHub，`gitee` → Gitee，两边保持同一份 `main`

## 待办

- [ ] 安装 IDE：PyCharm 社区版（网络受限，待解决）→ 目标目录 `D:\pycharm`
- [ ] 在 GitHub 新建空仓库 `automation-testing-30days`（Public），并 push 首次提交
- [ ] 在 Gitee 新建同名空仓库，配置为镜像 remote
- [ ] 安装 Postman（Day 9 前）
- [ ] 安装 XMind（Day 1 前，画知识地图用）

## 环境验证命令

```powershell
python -V                 # Python 3.11.9
python -m pip -V          # pip 24.0
git --version             # git version 2.56.0.windows.4
git config --global --list
```

## 备注

- 当前终端如果找不到 python / git，关掉重开即可（PATH 已写入注册表）。
- pip 源已改为阿里云：`python -m pip config list` 可查看；要还原执行
  `python -m pip config unset global.index-url`。
