# Task1724 · 区域特色产业 AI 赋能一期 · 零依赖版交付包

ClawHunt #1724 投标交付仓库，零依赖版原型（仅 Python 标准库 + 本地 JSON 存储）。

## 发布版本

| 版本 | 定位 | 核心代码 | 发布包 |
|---|---|---|---|
| v4.0 | 完整核心版（当前） | 保留全部核心实现，不去核心化 | 见 Releases / v4.0 |
| v1.0 / v2.0 | 去核心化骨架版 | 核心模块替换为占位桩 | 历史版本 |

## v4.0 说明

v4.0 保留完整核心代码，买方解压即得完整可跑实现，用于真实体验全部功能链路。

- 9 个核心模块与原型逐字节一致（SHA256 9/9）
- 包内实测：tests.py 125/125、verify.py all_green true、模块用例 14/14、docs_vs_impl 73/73、短剧样片 10/10
- 验收证据：verification/publish_v4.0_full_core_evidence.txt

下载：Releases → v4.0 → Task1724_prototype_publish_v4.0.zip