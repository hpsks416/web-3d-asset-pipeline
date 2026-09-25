# web-3d-asset-pipeline

准备和优化浏览器游戏的 3D 资产（GLB/glTF 2.0）：Blender 清理导出、碰撞/LOD 设置、压缩、纹理打包与运行时校验。

## 环境依赖

- 操作系统：Windows
- 运行时：无（纯指令型 skill，由 agent 直接执行）
- 第三方软件：Blender

## 目录结构

    web-3d-asset-pipeline/
    ├── SKILL.md    技能入口与工作流
    ├── agents\openai.yaml
    ├── references\alternative-3d-engines.md
    ├── references\gltf-loading-starter.md
    ├── references\rapier-integration-starter.md
    ├── references\react-three-fiber-stack.md
    ├── references\react-three-fiber-starter.md
    ├── references\three-hud-layout-patterns.md
    ├── references\three-webgl-architecture.md
    ├── references\threejs-stack.md
    ├── references\threejs-vanilla-starter.md
    ├── references\web-3d-asset-pipeline.md
    ├── references\webgl-debugging-and-performance.md

## 安装

    # GitHub
    git clone https://github.com/hpsks416/web-3d-asset-pipeline.git "$env:USERPROFILE\.dsh\skills\web-3d-asset-pipeline"
    # 或 Gitee（国内直连）
    git clone https://gitee.com/hpsks416/web-3d-asset-pipeline.git "$env:USERPROFILE\.dsh\skills\web-3d-asset-pipeline"

克隆后 DSH 自动重新发现，无需构建。

## License

MIT License. See [LICENSE](LICENSE).
