# RYSurvival-Next

基于 [RenYuan-MC/RYSurvival](https://github.com/RenYuan-MC/RYSurvival) 升级的 Minecraft 服务端整合包。

将核心更新至 **1.21.4**，并对插件进行了更新。

## ✨ 更新内容

### 🚀 核心与兼容性
- 服务端核心升级至 **Minecraft 1.21.4**。
- 支持 **1.7.2 - 26.2** 客户端连接。

### 🔌 插件优化
- 使用功能更多且更安全的 `AuthMe` 替换原有的 `CatSeedLogin`。
- 使用 `TAB` 替换原有的 `ScoreBoard` 插件，统一管理计分板 (Scoreboard) 与玩家列表 (Tablist)。
- 更新 `EssentialsX` 语言文件，使其与服务端整体风格保持一致。
- 使用 `Law` 替换原有的 `GlobalGamerules`，因为 `GlobalGamerules` 与 1.21.4 不兼容且 `Law` 功能更多。
- 移除了基岩版互通，因为维护起来太折腾。而且现在手机也能直接跑 Java 版了，没必要非得用基岩版连 Java 服（iOS 虽然会麻烦点）。

## 📥 安装与运行

### 方式一：
1. 前往 [Releases](../../releases) 页面下载整合包（可能不是最新）。
2. 解压后，**Windows 用户**直接双击 `start.bat` 即可启动。

   > 默认分配 2GB 运行内存。如需调整，请右键编辑 `start.bat` 修改 `-Xmx` 参数（例如改为 `-Xmx4G`）。

### 方式二：
1. 下载本仓库代码或直接获取 `Server` 文件夹。
2. 确保本地已安装 **Java 21**。
3. 自行配置启动命令运行服务端。

## 🎮 联机指南

### 🏠 本地测试
1. 启动服务端。
2. 打开 Minecraft 客户端（版本 1.7.2 - 26.2）。
3. 添加服务器，地址输入 `127.0.0.1` 即可进入。

### 🌐 公网联机
通过**端口映射**或**内网穿透**工具获取公网 IP 及端口，自行查阅相关教程，这里就不详细展开了。

## 🧩 核心与插件

**核心**：[Purpur](https://github.com/PurpurMC/Purpur) 1.21.4

**插件**：[AuraSkills](https://modrinth.com/plugin/auraskills), [AuthMe](https://modrinth.com/plugin/authmerereloaded), [BetterRTP](https://www.spigotmc.org/resources/.36081/), [Citizens](https://github.com/CitizensDev/Citizens2), [CMILib](https://www.spigotmc.org/resources/.87610/), [CommandBlocker](https://modrinth.com/plugin/commandblocker), [DeluxeMenus](https://modrinth.com/plugin/deluxemenus), [Essentials](https://modrinth.com/plugin/essentialsx), [EssentialsChat](https://modrinth.com/plugin/essentialsx-chat-module), [EssentialsSpawn](https://modrinth.com/plugin/essentialsx-spawn),
[GrimAC](https://modrinth.com/plugin/grimac), [Law](https://github.com/mouse0w0/law), [LiteSignIn](https://www.spigotmc.org/resources/.79584/), [LuckPerms](https://modrinth.com/plugin/luckperms), [MiniMOTD](https://modrinth.com/plugin/minimotd), [Multiverse-Core](https://modrinth.com/plugin/multiverse-core), [PlaceholderAPI](https://modrinth.com/plugin/placeholderapi), [PlayerPoints](https://www.spigotmc.org/resources/.80745/), [ProtocolLib](https://github.com/dmulloy2/ProtocolLib/), [QuickShop-Hikari](https://modrinth.com/plugin/quickshop-hikari),
[RenYuan-Core](https://github.com/RenYuan-MC/RenYuan-Core), [Residence](https://zrips.net/Residence/), [SkinsRestorer](https://modrinth.com/plugin/skinsrestorer), [Skript](https://modrinth.com/plugin/skript), [Slimefun](https://slimefun-wiki.guizhanss.cn/Installing-Slimefun), [TAB](https://modrinth.com/plugin/tab-was-taken), [Themis](https://modrinth.com/plugin/themis-anti-cheat), [TileDataSaver](https://www.spigotmc.org/resources/.85624/), [Vault](https://modrinth.com/plugin/vaultunlocked), [ViaBackwards](https://modrinth.com/plugin/viabackwards),
[ViaRewind](https://modrinth.com/plugin/viarewind), [ViaRewind-Legacy-Support](https://hangar.papermc.io/ViaVersion/ViaRewindLegacySupport), [ViaVersion](https://modrinth.com/plugin/viaversion)

## ⚖️ 许可证

本整合包基于 [RenYuan-MC/RYSurvival](https://github.com/RenYuan-MC/RYSurvival) 制作，沿用其许可协议 [Creative Commons Attribution Share Alike 4.0 International](../../blob/main/LICENCE)。

本整合包运行所需的第三方服务端核心（Purpur）及插件均遵循其各自的开源协议，版权归原作者或团队所有，请使用者遵守相应协议。
