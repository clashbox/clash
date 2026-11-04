<div align="center">
  <a href="https://github.com/clashbox/clash" title="Clash 分步下载与安装核对">
<img width="150" height="150" alt="Clash" src="https://github.com/user-attachments/assets/43b0c4b5-4ec2-42b7-87f5-2cde0e6d4e13" />

  </a>
  <h1>Clash 分步下载与安装核对 (2026年11月更新)</h1>
  <p>
    <b>从选系统到安装后自检的一条路线图</b>
  </p>
  <p>
    <img src="https://img.shields.io/badge/Update-2026.11-brightgreen.svg" alt="Update">
    <img src="https://img.shields.io/badge/Platform-Win%20%7C%20Mac%20%7C%20iOS%20%7C%20Android%20%7C%20Linux-blue.svg" alt="Platform">
    <img src="https://img.shields.io/badge/Ecosystem-Clash%20%7C%20Mihomo%20%7C%20Sing--box%20%7C%20Xray-orange.svg" alt="Ecosystem">
  </p>
</div>

如果你觉得这个项目对你有帮助，欢迎点右上角的**Star**⭐ 支持一下！

[代理雷达](https://github.com/guiforcores/dailileida)：每日追踪 mihomo、sing-box、Xray、V2Ray、Clash 及自研内核的代理客户端：开源项目看 GitHub Star，商店应用看美区 App Store / Google Play 评分数。

[节点雷达](https://jiedianleida.com/)：安装核对后的订阅旁证——免费 V2Ray / Clash / SS / Trojan 节点每日测速，导入前先看延迟与存活。

**本页路线：** [说明](#1-本页说明) · [总表](#2-资源总表) · [分系统](#3-分系统下载路线) · [安装核对](#4-安装后核对) · [停更](#5-停更对照) · [订阅](#6-订阅参考可选) · [问答](#7-常见问题) · [免责](#8-免责声明)

---

## 1. 本页说明

本仓库按 **Clash 分步下载与安装核对** 整理：用「分步路线」把仍在维护的客户端、停更备份、订阅旁证和注意项串成一条阅读路径，方便按系统落到官方 **GitHub Releases**。

| 本页提供 | 本页不提供 |
|:---------|:-----------|
| 指向各项目官方 **GitHub Releases**（或明确标注的备份仓）的入口 | 安装包镜像附件、破解包、不明 IPA |
| 按系统排列的下载路线与通用装机注意 | 逐步图文安装长教程（以各仓库 README / Issues 为准） |
| 停更客户端的存档对照，避免误下旧主程序 | 托管节点、代生成订阅、保证某一机场可用性 |
| 月份维护标记：`YYYY年M月更新` 与 `Update-YYYY.MM` | 把「本页维护月」当成某一客户端发版日 |

标题里的日期与绿色徽章由例行任务同步，**请保持这两种格式不要改乱**。它们只表示本页最近整理月份。

---

## 2. 资源总表

建议阅读顺序：先看总表定位角色 → 再进 [分系统下载路线](#3-分系统下载路线) 点 Releases → 装完做 [安装后核对](#4-安装后核对)。

| 类别 | 内容 | 你要做什么 |
|:-----|:-----|:-----------|
| 桌面 GUI | Windows / macOS / Linux 维护中客户端 | 打开对应 Releases，按 OS + 架构选 Assets |
| 移动端 | Android / iOS 维护中客户端 | Android 走维护仓；iOS 只跟官方说明 / 商店 |
| 跨端工具 | 同一订阅希望少换 App 时 | 再看 Clash Mi / Hiddify / FlClash |
| 停更存档 | 已停更经典客户端 | 仅历史对照，不建议日常主用 |
| 热度旁证 | [代理雷达](https://github.com/guiforcores/dailileida) | 看 Star / 商店评分，**不是**下载源 |
| 订阅参考 | 机场整理（可选） | 自行甄别合规与稳定性；本仓不托管节点 |

> 软路由 / OpenWRT 一般不和桌面 GUI 共用同一套 Assets。请查固件插件源或 mihomo 相关文档，并与手机、电脑配置分开备份。

---

## 3. 分系统下载路线

每一段是一条「按系统走的下载路线」：主链一律落到官方 Releases。顺序按常见使用场景排列，**不是**销量排行。

### Windows

| 优先级 | 客户端 | Releases |
|:------:|:-------|:---------|
| 1 | Clash Verge Rev | [clash-verge-rev/clash-verge-rev](https://github.com/clash-verge-rev/clash-verge-rev/releases) |
| 2 | Clash Party | [mihomo-party-org/clash-party](https://github.com/mihomo-party-org/clash-party/releases) |
| 3 | FlClash | [chen08209/FlClash](https://github.com/chen08209/FlClash/releases) |
| 4 | Clash Mi | [KaringX/clashmi](https://github.com/KaringX/clashmi/releases) |
| 5 | Clash Nyanpasu | [LibNyanpasu/clash-nyanpasu](https://github.com/LibNyanpasu/clash-nyanpasu/releases) |

补充： [Bettbox](https://github.com/appshubcc/Bettbox/releases) · [Sparkle](https://github.com/xishang0128/sparkle/releases)。选包时核对 `x64` / `arm64` 与安装器后缀（exe / msi 等）。

### macOS

| 优先级 | 客户端 | Releases |
|:------:|:-------|:---------|
| 1 | ClashX Meta | [MetaCubeX/ClashX.Meta](https://github.com/MetaCubeX/ClashX.Meta/releases) |
| 2 | Clash Verge Rev | [clash-verge-rev/clash-verge-rev](https://github.com/clash-verge-rev/clash-verge-rev/releases) |
| 3 | Clash Party | [mihomo-party-org/clash-party](https://github.com/mihomo-party-org/clash-party/releases) |
| 4 | FlClash / Clash Mi | [FlClash](https://github.com/chen08209/FlClash/releases) · [Clash Mi](https://github.com/KaringX/clashmi/releases) |

注意区分：**ClashX Meta（维护中）** ≠ 下方停更对照里的经典 **ClashX（已停更）**。Apple Silicon 与 Intel 构建不要混下。

### Linux

| 优先级 | 客户端 | Releases |
|:------:|:-------|:---------|
| 1 | Clash Verge Rev | [releases](https://github.com/clash-verge-rev/clash-verge-rev/releases) |
| 2 | Clash Party | [releases](https://github.com/mihomo-party-org/clash-party/releases) |
| 3 | FlClash | [releases](https://github.com/chen08209/FlClash/releases) |
| 4 | Clash Nyanpasu / Clash Mi | [Nyanpasu](https://github.com/LibNyanpasu/clash-nyanpasu/releases) · [Clash Mi](https://github.com/KaringX/clashmi/releases) |

按发行版挑选 AppImage / deb / rpm / 压缩包；TUN 与权限问题优先查对应仓库 Issues。

### Android

| 优先级 | 客户端 | Releases |
|:------:|:-------|:---------|
| 1 | Clash Meta for Android | [MetaCubeX/ClashMetaForAndroid](https://github.com/MetaCubeX/ClashMetaForAndroid/releases) |
| 2 | FlClash | [chen08209/FlClash](https://github.com/chen08209/FlClash/releases) |
| 3 | Clash Mi | [KaringX/clashmi](https://github.com/KaringX/clashmi/releases) |
| 4 | ClashBox | [xiaobaigroup/ClashBox](https://github.com/xiaobaigroup/ClashBox/releases) |

勿与停更对照「Clash for Android」混淆——那是已停更的经典客户端备份。

### iOS / 多端

| 场景 | 先看 | 说明 |
|:-----|:-----|:-----|
| iOS | [Clash Mi](https://github.com/KaringX/clashmi/releases) · [Hiddify](https://github.com/hiddify/hiddify-app/releases) | **仅**官方说明或商店渠道；本页不索引来路不明的 IPA |
| 希望多端少换工具 | Clash Mi · Hiddify · FlClash | Hiddify 配置模型可能与纯 Clash YAML 不完全对应，导入前读该仓说明 |
| 热度旁证 | [代理雷达](https://github.com/guiforcores/dailileida) | 看 Star / 商店评分，不代替 Releases |

---

## 4. 安装后核对

按路线取到安装包之后，建议走完下面通用步骤（各客户端细节以官方文档为准）：

1. **只从上方 Releases（或本页标明的备份仓）下载**，不要用搜索引擎随意点的「高速下载站」。  
2. 打开 Release 正文：优先 **Latest** 正式版；Pre-release 仅在你明确要尝鲜时使用。  
3. 在 Assets 里按操作系统与 CPU 架构挑选；体积异常或文件名与说明不符时先停手。  
4. 若正文提供 SHA / 校验和，下载后本地核对再安装。  
5. Windows 遇 SmartScreen / 杀软提示、macOS 遇「无法验证开发者」时，先回到**同一** Release 页核对包名，再决定是否放行。  
6. 导入你自己的订阅 / 配置 → 测延迟 → 再开系统代理或 TUN。  
7. 不要同时开多个同类系统代理 / VPN 工具，容易互相抢路由。

教程站点（可选对照，仍以 GitHub 发布页为准）：  
[clashverge.com](https://clashverge.com/) · [clash-party.org](https://clash-party.org/) · [clash-mi.org](https://clash-mi.org/) · [clashxmeta.org](https://clashxmeta.org/) · [clashmetaforandroid.org](https://clashmetaforandroid.org/) · [getflclash.org](https://getflclash.org/) · [gethiddify.org](https://gethiddify.org/) · [clashbox.org](https://clashbox.org/)

---

## 5. 停更对照

以下项目**已停更或仅作历史对照**。可以查阅，不建议当作日常主客户端。

| 项目 | 备份 / 原仓库 | 教程（存档向） |
|:-----|:--------------|:---------------|
| Clash for Windows | [clash-latest/Clash-for-Windows](https://github.com/clash-latest/Clash-for-Windows) | [clashforwindows.org](https://clashforwindows.org/) |
| ClashX | [clash-latest/ClashX](https://github.com/clash-latest/ClashX) | [clashx.org](https://clashx.org/) |
| Clash for Android | [clash-latest/Clash-for-Android](https://github.com/clash-latest/Clash-for-Android) | [clashforandroid.org](https://clashforandroid.org/) |
| Clash Verge（原版） | [zzzgydi/clash-verge](https://github.com/zzzgydi/clash-verge/releases) | [clashverge.org](https://clashverge.org/) |
| ClashN | [2dust/clashN](https://github.com/2dust/clashN/releases) | [getclashn.org](https://getclashn.org/) |

日常请回到 [分系统下载路线](#3-分系统下载路线) 选仍在维护的客户端。

---

## 6. 订阅参考（可选）

本仓库**不托管、不出售、不保证**任何节点。若你需要付费机场，可自行查阅下列整理页（含优惠入口时请自行甄别合规性、稳定性与退订规则）：

| 名称 | 简介 | 链接 |
|:-----|:-----|:-----|
| 扬帆云 | IPLC 专线向 | [优惠入口](https://clashdev-github.affout.com/yangfanyun/) |
| 尔湾云 | 性价比专线向 | [优惠入口](https://clashdev-github.affout.com/erwan/) |
| 大哥云 | 老牌中转向 | [优惠入口](https://clashdev-github.affout.com/dageyun/) |
| 龙猫云 | 高品质专线向 | [优惠入口](https://clashdev-github.affout.com/totorocloud/) |
| 肥猫云 | 大带宽专线向 | [优惠入口](https://clashdev-github.affout.com/fatcatcloud/) |

更多整理：[ClashNode](https://github.com/clash-latest/ClashNode) · [clash.dev/node](https://clash.dev/node/)

没有订阅时，客户端仍然可以安装，只是没有可用代理配置。

---

## 7. 常见问题

**Q：这个「中文分享」页和其它同名资源页有什么不一样？**  
A：本页用「分步路线」叙事：说明 → 资源总表 → 分系统下载 → 安装核对 → 停更对照 → 订阅参考。不做平台选型总表，也不做官网核对长清单，也不做 Wiki 词条长文。

**Q：Clash、Mihomo、Clash Meta 是什么关系？**  
A：口语里的 Clash 常泛指能导入 Clash 风格配置的客户端。原核心停更后，许多维护中 GUI 改用 Mihomo（常称 Clash Meta 系）等兼容内核。选型以具体 GitHub 组织 / 仓库为准。

**Q：为什么不在本仓库直接挂安装包？**  
A：版本迭代快，附件易过期且难校验。以各项目 GitHub Releases 为准最稳妥。

**Q：iOS 能不能随便下个 IPA？**  
A：不建议。请按 [Clash Mi](https://github.com/KaringX/clashmi/releases) / [Hiddify](https://github.com/hiddify/hiddify-app/releases) 官方说明或商店渠道安装。

**Q：标题月份和徽章谁负责改？**  
A：例行任务会更新 `YYYY年M月` 与 `Update-YYYY.MM`；改文案时请保留这两种格式。

---

## 8. 免责声明

- 本页仅为开源客户端与相关资源的**索引导航**，不提供绕过审查、侵犯版权或从事违法活动的服务或教程。  
- 请遵守你所在地区的法律法规及各服务条款；因使用第三方客户端、订阅或节点产生的风险与后果由使用者自行承担。  
- 第三方网站、机场与优惠链接的内容、价格、可用性随时可能变化，本仓库不作担保。  
- Logo 与页面入口指向本仓库：[clashbox/clash](https://github.com/clashbox/clash)。
