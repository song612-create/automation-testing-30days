# 30 天自动化测试学习记录

目标岗位：软件测试工程师 / 自动化测试 / 测试开发（初级）
计划周期：2026-11-05 — 2026-12-04（Day 1–30）
详细计划：见本地《30天软件自动化测试入行计划.docx》与《30天学习打卡表.xlsx》

## 环境

| 工具 | 版本 | 位置 |
|---|---|---|
| Python | 3.11.9 | `D:\python` |
| pip | 24.0（阿里云源） | `D:\python\Scripts\pip.exe` |
| Git | 2.56.0 | `D:\git` |
| 编辑器 | PyCharm / VS Code / IDLE | 待定 |

## 目录结构

```
automation-testing-30days/
├── 01_functional_testing/      # 第 1 周：功能测试
│   ├── test-plan/              # 测试计划
│   ├── test-cases/             # 用例（Excel / XMind 导出）
│   ├── bug-reports/            # 缺陷报告
│   └── test-report/            # 测试报告
├── 02_api_testing/             # 第 2 周：接口测试
│   ├── postman/                # Postman 集合与环境
│   └── pytest/                 # pytest + requests 入门用例
├── 03_ui_automation/           # 第 3 周：UI 自动化（POM）
│   ├── pages/                  # 页面对象
│   └── testcases/              # 测试用例
├── 04_final_project/           # 第 4 周：综合实战 + 作品集
├── notes/                      # 每日笔记（YYYY-MM-DD.md）
├── requirements.txt
└── .gitignore
```

## 进度

| 周次 | 主题 | 核心产出 | 状态 |
|---|---|---|---|
| W1（Day 1–7） | 功能测试：用例设计、缺陷管理 | 65 条用例 + 10 条缺陷 + 测试报告 | ⬜ 未开始 |
| W2（Day 8–14） | Python、HTTP、Postman、抓包、SQL、Linux | Postman 集合 + 20 条 SQL + 10 个 pytest 用例 | ⬜ 未开始 |
| W3（Day 15–21） | pytest 框架、Selenium + POM、Git、CI | 接口框架 + UI 框架 + 2 条流水线 | ⬜ 未开始 |
| W4（Day 22–30） | 性能、Docker、综合实战、简历、投递 | 作品集 + 简历 + 20 家投递 | ⬜ 未开始 |

> 每完成一周，把「⬜ 未开始」改成「✅ 已完成」，并在下面补一行本周结论。

## 每日记录约定

1. 每天在 `notes/` 下新建 `YYYY-MM-DD.md`，写三行：学到什么 / 卡在哪 / 明天第一件事。
2. 当天产出的文件按周归到对应目录，文件名带日期，例如 `2026-11-07-登录用例.xlsx`。
3. 每天至少一次 commit，提交信息写清楚做了什么：
   - `feat(w1): 完成登录/注册/搜索 45 条用例`
   - `fix(w2): 修正 Postman 断言中的状态码判断`
   - `docs: 补充第 1 周测试报告`

## 备注

- 本仓库同时作为求职作品集的「过程证据」：面试时能拿出 30 天的提交记录，比任何自我评价都有说服力。
- 测的是公开练习站（saucedemo.com、petstore.swagger.io），不涉及任何公司真实数据。
