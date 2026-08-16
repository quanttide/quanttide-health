# quanttide-health

量潮健康管理

## 概述

量潮健康管理（quanttide-health）是量潮知识管理体系中的**健康管理**领域，强调身心健康的平衡，面向个人、家庭、企业等主体。健康数据属高度敏感信息，本领域**特别重视数据安全**。

## 领域边界

- **个人健康**：相对全面的健康管理——体检、运动、睡眠、营养，以及情绪与压力管理
- **家庭健康**：以大病管理为主——重疾风险、病程跟踪、家庭协同照护
- **企业健康**：以共同问题管理为主——如知识工作的过疲劳、职业健康与健康福利
- **健康数据安全**：健康档案与指标属敏感数据，加密、脱敏、访问控制与审计为本领域底线（与安全工程领域协同）

## 子模块

| 路径 | 说明 |
|------|------|
| `apps/qtcloud-health` | QtCloud 健康云 (git submodule) |
| `packages/quanttide-health-toolkit` | 健康管理工具集 (git submodule) |
| `examples/default` | 健康管理实验室 (git submodule → quanttide-laboratory-of-health-management) |
| `data/context` | 健康管理语境 (git submodule → quanttide-context-of-health-management) |
| `data/journal` | 健康管理日志 (git submodule → quanttide-journal-of-health-management) |

## 许可

[CC BY 4.0](LICENSE)
