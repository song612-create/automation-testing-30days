# Day 0 · 环境准备记录（2026-11-04）

## 已完成

- [x] Python 3.11.9 安装到 `D:\python`，已加入用户 PATH
- [x] pip 24.0 可用，已配置阿里云镜像（清华源当时返回 403）
- [x] Git 2.56.0 安装到 `D:\git`，已在机器 PATH
- [x] Git 全局身份：`song <1377958869@qq.com>`
- [x] Git 中文与换行相关配置：`init.defaultBranch=main`、`core.autocrlf=true`、`core.quotepath=false`、`i18n.*Encoding=utf-8`
- [x] 项目仓库初始化：`D:\projects\automation-testing-30days`
- [x] GitHub 账号注册：`song612-create`
- [x] 首次推送成功，`main` 已上 GitHub

## 远程仓库

- GitHub 作为主仓库（简历通用），Gitee 作为国内镜像（快、抗抽风）
- 约定：`origin` → GitHub，`gitee` → Gitee，两边保持同一份 `main`

| remote | 地址 | 状态 |
|---|---|---|
| origin | https://github.com/song612-create/automation-testing-30days.git | ✅ 已推送 |
| gitee | 待补充 | ⬜ 未配置 |

## 待办

- [ ] 安装 IDE：PyCharm 社区版（网络受限，待解决）→ 目标目录 `D:\pycharm`
- [ ] 在 Gitee 新建同名空仓库，配置为镜像 remote
- [ ] 安装 Postman（Day 9 前）
- [ ] 安装 XMind（Day 1 前，画知识地图用）

## 环境验证命令

```powershell
python -V                 # Python 3.11.9
python -m pip -V          # pip 24.0
git --version             # git version 2.56.0.windows.4
git config --global --list
git remote -v
```

## 备注

- 当前终端如果找不到 python / git，关掉重开即可（PATH 已写入注册表）。
- pip 源已改为阿里云：`python -m pip config list` 可查看；要还原执行
  `python -m pip config unset global.index-url`。
- 曾发现全局配置里有 `http.sslVerify=false`（会关闭 HTTPS 证书校验，推送凭证有被中间人截获的风险），
  已于 2026-11-04 移除；移除后实测 GitHub / Gitee 推送与拉取均正常，现在走默认的证书校验。
