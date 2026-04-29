# Student Era — 课程设计归档

> 基于 pnpm workspace 的 Monorepo，汇总学生时代的各类课程设计项目。

## 项目索引

| 学期 | 课程 | 项目路径 | 技术栈 |
|------|------|---------|--------|
| 2026 春 | 大数据可视化 | [`projects/bigdata-visualization`](./projects/bigdata-visualization) | Vue 3 + TypeScript + ECharts + Element Plus |

## 快速启动

```bash
# 安装根依赖
pnpm install

# 启动大数据可视化项目
pnpm dev:visualization
```

## 目录结构

```
.
├── packages/              # 共享包（未来扩展）
├── projects/              # 课程设计项目
│   └── bigdata-visualization/
│       ├── src/
│       └── docs/          # 课程设计报告
└── package.json           # workspace root
```
