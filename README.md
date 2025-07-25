<h1 align="center">💦 BPB Panel</h1>

### 🌏面板截图 

<p align="center">
  <img src="docs/assets/images/panel-overview.jpg">
</p>
<br>

## 简介
该项目致力于为 [yonggekkk](https://github.com/yonggekkk) 创建的 [Cloudflare-workers/pages 代理脚本](https://github.com/yonggekkk/Cloudflare-workers-pages-vless) 开发用户面板。该面板提供两种部署选项：
- **Worker** 部署
- **Pages** 部署
<br>

🌟 如果您发现 **BPB Panel** 很有价值，您的捐赠将大有裨益 🌟
- **USDT (BEP20)：**`0x111EFF917E7cf4b0BfC99Edffd8F1AbC2b23d158`

## 功能

1. **免费**：无需任何费用。
2. **用户友好面板**：设计用于轻松导航、配置和使用。
3. **协议**：提供 VLESS、Trojan 和 Wireguard (Warp) 协议。
4. **Warp Pro 配置**：针对关键情况优化 Warp。
5. **支持 Fragment**：支持 Fragment 功能，适用于关键网络情况。
6. **完整路由规则**：绕过伊朗/中国/俄罗斯和局域网，阻止 QUIC、色情、广告、恶意软件、网络钓鱼……
7. **链代理**：能够添加链代理来修复 IP。
8. **支持广泛的客户端**：为 Xray、Sing-box 和 Clash 核心客户端提供订阅链接。
9. **密码保护面板**：使用密码保护来保护您的面板。
10. **完全可定制：**能够使用在线扫描仪并设置干净的 IP 域、代理 IP、设置 DNS 服务器、选择端口和协议、Warp 端点...
<br>

## 如何使用：
- [安装（Pages - 新的推荐方法）](docs/pages_upload_installation_fa.md)

- [安装（Pages）](docs/pages_installation_fa.md)

- [安装（Worker）](docs/worker_installation_fa.md)

- [如何使用](docs/configuration_fa.md)

- [常见问题](docs/faq.md)
<br>

## 支持的客户端
| 客户端 | 版本 | 片段 | Warp Pro |
| :-------------: | :-------------: | :-------------: | :-------------: |
| **v2rayNG** | 1.9.33 或更高版本 | :heavy_check_mark: | :heavy_check_mark: |
| **v2rayN** | 7.8.3 或更高版本 | :heavy_check_mark: | :heavy_check_mark: |
| **v2rayN-PRO** | 1.8 或更高版本 | :heavy_check_mark: | :heavy_check_mark: |
| **Husi** | | :x: | :x: |
| **Sing-box** | 1.11.2 或更高版本 | :x: | :x: |
| **Streisand** | 1.6.48 或更高版本 | :heavy_check_mark: | :heavy_check_mark: |
| **V2Box** | | :x: | :x: |
| **Shadowrocket** | | :x: | :x: |
| **Nekoray** | | :heavy_check_mark: | :x: |
| **Hiddify** | 2.5.7 或更高版本 | :heavy_check_mark: | :heavy_check_mark: |
| **NikaNG** | | :heavy_check_mark: | :heavy_check_mark: |
| **Clash Meta** | | :x: | :x: |
| **Clash Verge Rev** | | :x: | :x: |
| **FLClash** | | :x: | :x: |

## 环境变量
| 变量 | 用法 |
| :-------------: | :-------------: |
| **UUID** | VLESS UUID |
| **TR_PASS** | 木马密码 |
| **PROXYIP** | 代理 IP 或域（VLESS、木马） |
| **SUB_PATH** | 订阅的 URI |
| **FALLBACK** | 后备域（VLESS、木马） |
| **DOH_URL** | 核心 DOH |
