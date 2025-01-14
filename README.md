# monitoring-buried-points 前端监控埋点

采用 pnpm + monorepo 进行管理

## 目录结构

```
- docs 文档
- packages
    - monitor-core 监控核心
    - monitor-server 后端服务（采用 nest.js 开发）
    - monitor-web 前端监控（采用 next.js 开发）
- scripts 脚本
```

## 命令

> 请使用 pnpm@7 进行依赖安装

```bash
# 安装依赖
pnpm in
```

## git提交规范

需要全局安装 `commitizen`

```bash
pnpm add -g commitizen
```

用 git cz 命令代替 git commit