# web-3d-asset-pipeline

Prepare and optimize browser-game 3D assets. Use when the user asks for GLB or glTF shipping work, including Blender cleanup and export, collision or LOD setup, compression, texture packaging, and runtime validation.

## 这是什么

DSH（DeepSeek Harness）skill —— 一个可由 AI agent 按需自动加载的能力单元。克隆到 skill 目录后，DSH 会依据上方描述自动发现并触发它，无需构建。

## 安装

最简单：用 [dsh-config](https://github.com/hpsks416/dsh-config) 的一键脚本 `install.ps1` 批量安装全部 skill。单个安装：

    # GitHub
    git clone https://github.com/hpsks416/web-3d-asset-pipeline.git "$env:USERPROFILE\.dsh\skills\web-3d-asset-pipeline"
    # 或 Gitee（国内直连更快）
    git clone https://gitee.com/hpsks416/web-3d-asset-pipeline.git "$env:USERPROFILE\.dsh\skills\web-3d-asset-pipeline"

克隆后 DSH 会自动重新发现，无需重启。更新用：

    git -C "$env:USERPROFILE\.dsh\skills\web-3d-asset-pipeline" pull

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

## 依赖

无运行时依赖，纯指令型 skill（由 agent 直接执行 Markdown 工作流）。

## License

MIT License. See [LICENSE](LICENSE).
