# MTR-Station-Decoration-Addon

<h2>A Station Decoration Addon for the Minecraft Transit Railway Mod</h2>

## Setup

<h3>
   1. Clone this repository
</h3>
<h3>
   2. Switch a Minecraft version
</h3>
<h3>
   3. Sync the Gradle project
</h3>

## Link

<div id="source" class="image-t">
   <a href="https://modrinth.com/mod/minecraft-transit-railway">
      <img id="mtr" src="./image/logo.png" alt="Minecraft Transit Railway" width="128">
   </a>
   <a href="https://modrinth.com/mod/station-decoration">
      <img id="msd" src="./fabric/src/main/resources/icon.png" alt="MTR-Station-Decoration-Addon" width="128">
   </a>
   <a href="https://www.zbx1425.cn/nautilus/mtr-nte/">
      <img id="nte" src="./image/icon_nte.png" alt="Nemo's Transit Expansion" width="128">
   </a>
   <a href="https://discord.gg/PVZ2nfUaTW">
      <img id="mtr_discord" src="./image/discord.png" alt="MTR Discord" width="128">
   </a>
</div>

## License

[MIT License](https://raw.githubusercontent.com/AIDA64S/MTR-Station-Decoration-Addon/master/LICENSE)

## Thanks

<div id="jb_b" class="image-h">
   <a href="https://www.jetbrains.com/code-with-me/">
      <img id="code-with-me" src="./image/CodeWithMe.png" alt="Code With Me" width="1000">
   </a>
   <a href="https://www.jetbrains.com/idea/">
      <img id="idea" src="./image/IntelliJ_IDEA.png" alt="Intellij IDEA" width="1000">
   </a>
</div>
<div id="jb_t" class="image-container">
   <a href="https://www.jetbrains.com" >
      <img id="jb_beam" src="./image/jb_beam.png" alt="Jetbrains" width="300">
   </a>
   <a href="https://www.jetbrains.com/idea/" >
      <img id="idea_icon" src="./image/IntelliJ_IDEA_icon.png" alt="Intellij IDEA" width="300">
   </a>
</div>

---

## RongMC · Minecraft 26.3 Fabric 移植说明

本仓库是 RongMC 维护的 **Minecraft 26.3 / Fabric / Java 25** 移植构建，不是上游官方发行渠道。

### 与原版的主要差异
- Minecraft 26.3 Fabric 移植；Fabric id `rongmc_msd`（provides `msd`）。
- 依赖 `rongmc_mtr`。上游 README 的 MIT 说明保留作溯源；本发布仓许可证见 `LICENSE`（GPL-3.0）。

### 已知问题 / 限制
- 装饰向附属，功能随 MTR 核心版本；若核心 API 再变需要重新适配。
- 含自有 HTTP/数据加载逻辑，服务端日志会出现 MSD server 相关输出属正常。

### 构建与安装
- Fabric mod id：`rongmc_msd`（`provides`：`msd`，旧依赖名一般仍可解析）
- Release 产物见本仓库 Releases（jar 名带 `rongmc-` 前缀）
- 许可证：本仓以 **GPL-3.0** 发布（见 `LICENSE`）；请同时尊重上游原作者条款与署名

