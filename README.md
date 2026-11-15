# Task1724 · 区域特色产业 AI 赋能一期 · 零依赖版交付包

ClawHunt #1724 投标交付仓库，零依赖版原型（仅 Python 标准库 + 本地 JSON 存储）。

## 发布版本

| 版本 | 定位 | 核心代码 | 状态 | 发布包 |
|---|---|---|---|---|
| v4.1 | 零依赖版 · 完整核心版（当前最新，**提交客户版本**） | 保留全部核心实现，不去核心化 | 当前 | Releases / v4.1 |
| v4.0 | 零依赖版 · 完整核心版（历史版本） | 保留全部核心实现，不去核心化 | 历史 | Releases / v4.0 |
| heavy-v1.0 | 重技术栈版（FastAPI + PostgreSQL + Docker Compose）发布包 | 去核心化（de-cored）骨架包 | 当前（重技术栈版唯一版本） | Releases / heavy-v1.0 |
| v1.0 / v2.0 | 零依赖版早期去核心化骨架版（历史，已被 v4.x 取代） | 核心模块替换为占位桩 | 历史 | 保留原样 |

> 版本关系说明：`v1.0 / v2.0` 指零依赖版的早期骨架版本，**不是**重技术栈版的版本号；重技术栈版至今只发布过 `heavy-v1.0`，**没有 v2.0**。

## v4.1 说明（当前交付版本）

v4.1 为零依赖版完整核心版，**本次提交给客户的即为 v4.1**；在 v4.0 基础上重建导航控制台（顶部栏 + 左侧侧边栏，含折叠、响应式与三语切换）。

- 9 个核心模块与原型逐字节一致（SHA256 9/9）
- 包内实测：tests.py 125/125 OK、verify.py VERIFY PASS（all_green true）、模块 A/B/C/D 全 PASS、docs_vs_impl 73/73 ALL PASS、短剧样片 10/10、demo.py 端到端全通过、Web 服务 GET / 与 /api/health 均返回 200
- 验收证据：`verification/publish_v4.1_full_core_evidence.txt`

下载：Releases → v4.1 → `Task1724_prototype_publish_v4.1.zip`

## v4.0 说明（历史版本）

v4.0 保留完整核心代码，买方解压即得完整可跑实现，用于真实体验全部功能链路。

- 9 个核心模块与原型逐字节一致（SHA256 9/9）
- 包内实测：tests.py 125/125、verify.py all_green true、模块用例 14/14、docs_vs_impl 73/73、短剧样片 10/10
- 验收证据：`verification/publish_v4.0_full_core_evidence.txt`

下载：Releases → v4.0 → `Task1724_prototype_publish_v4.0.zip`

## 重技术栈版（heavy-v1.0）

- 下载：Releases → heavy-v1.0 → `Task1724_prototype_heavy_publish_v1.0.zip`
- 该发布包为去核心化形态；完整可跑实现以零依赖版 v4.1 为准
