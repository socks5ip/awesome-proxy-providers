# awesome-proxy-providers

> 代理IP / 住宅IP 服务商精选清单与横向对比（中文面向）。覆盖 SOCKS5、HTTP、住宅IP、机房IP，附最新**专属邀请码/优惠**。
> 由 [全网低价IP](https://socks5ip.com.cn) 维护 —— 一个聚合 20+ 服务商的导航对比平台。

本清单用于帮助你**快速选型与避坑**，所有服务商均支持**免费测试、先测后买**。

## 目录

- [什么是代理IP](#什么是代理ip)
- [服务商横向对比](#服务商横向对比)
- [按场景选型](#按场景选型)
- [免费检测方法](#免费检测方法)
- [避坑指南](#避坑指南)
- [聚合导航与联系](#聚合导航与联系)

## 什么是代理IP

代理IP 是介于本机与目标服务器之间的中转节点，用于隐藏真实出口 IP。常见类型：

- **住宅IP（Residential）**：由 ISP 分配给家庭宽带的真实 IP，匿名度高，适合风控严格的业务。
- **机房IP（Datacenter）**：来自云厂商/IDC，成本低、速度快，适合批量数据采集。
- **静态住宅IP**：住宅属性 + 固定不变，兼顾稳定与匿名。
- **动态住宅IP**：每次连接更换出口，适合需要高频换 IP 的场景。

协议上常见 **SOCKS5**（支持 UDP、全局转发）与 **HTTP/HTTPS**（适合网页与 API）。

## 服务商横向对比

> 价格随活动浮动，以官网实时为准。「邀请码」为读者专属优惠，注册时填入即可享额外福利。

| 服务商 | 起步价 | 类型侧重 | 邀请码 / 备注 |
|--------|--------|----------|---------------|
| [奔富IP](https://user.benfuip.com/main/register?aff=adminA1) | 2.6 元/月 | SOCKS5/住宅 | `adminA1` |
| [天行IP](http://www.tianxingip.com/proxy/index/index/code/tianxingA0/p/2242.html) | 6 元/月 | 动态/静态 | `tianxingA0` |
| [沧海IP](http://www.canghaiip.com/#/register?invitation=YAXI&shareid=913) | 4 元/月 | 住宅/机房 | `YAXI` |
| [无双IP](https://new.6nn.net/admin#/login?scope=register&inviteCode=nBhBjh3kGW39) | 7.5 元/月 | SOCKS5 专线 | `nBhBjh3kGW39` |
| [全球代理IP](https://socks5ip.6nn.net/register) | 5 元/月 | 全球住宅 | 无码直注 |
| [55游](https://55u.net/#/login?c=adminA1) | 0.6 元/天 | 游戏/动态 | `adminA1` |
| [光梭IP](https://guangsuoip.com/user/login?p=guangsuoip&code=adminA8) | 2.24 元/月 | 高速机房 | `adminA8` |
| [JiuIP](https://jiuip.com/#/r?p=adminA0) | 3.4 元/月 | 住宅/机房 | `adminA0` |
| [光子IP](http://www.gzsk5.com/#/register?invitation=adminA1&shareid=231) | 4 元/月 | 住宅/机房 | `adminA1` |
| [糖果IP](http://www.tangguoip.com/register/800659) | 5 元/月 | 动态住宅 | `800659` |
| [优众IP](https://sk5ip.cn/views/login.html#?promotionCode=8F6A590B1DFB4F4C99D8E775B8AC51DC) | 7.2 元/月 | 企业级 | `8F6A590B1DFB4F4C99D8E775B8AC51DC` |
| [鲸云IP](https://console.51tcp.com/auth/register?i=degj) | 6 元/月 | 云原生 | `i=degj` |

> 以上仅为部分在架服务商。**全部 20+ 家实时对比、价格、邀请码、免费测试入口，见聚合导航 [socks5ip.com.cn](https://socks5ip.com.cn)。**

## 按场景选型

| 场景 | 推荐类型 | 说明 |
|------|----------|------|
| 跨境电商（多店铺） | 静态住宅IP | 固定出口，避免关联 |
| 社媒运营（多账号） | 住宅IP | 真实家庭 IP，降低风控 |
| 数据采集 / 爬虫 | 机房IP + 动态IP | 成本优先，高频换 IP |
| 游戏多开 | 动态住宅/机房 | 低延迟、稳定不掉线 |
| 广告验证 | 住宅IP | 模拟真实用户地区 |

## 免费检测方法

在选用前，务必验证代理是否可用、是否泄露真实 IP：

- 在线工具：[IP 质量检测](https://socks5ip.com.cn/ip-check) · [线路检测](https://socks5ip.com.cn/proxy-check)
- 命令行：[proxy-checker-cli](https://github.com/socks5ip/proxy-checker-cli) —— 支持 SOCKS5/HTTP 连通性、延迟、匿名度、出口IP 检测，零依赖。
- 脚本库：[proxy-resource-hub](https://github.com/socks5ip/proxy-resource-hub) —— 含 SOCKS5 连通性检测脚本。

## 避坑指南

1. **先测后买**：任何服务商都应提供免费测试额度，拒绝"不测直接付费"。
2. **看匿名度**：透明代理会泄露真实 IP，优先高匿。
3. **看 IP 纯净度**：被滥用的 IP 段容易被目标站点封禁。
4. **看售后与更换**：IP 失效能否快速换、是否有客服响应。
5. **警惕超低价**：远低于市场价的"独享住宅IP"多为共享/IP 池复用。

## 聚合导航与联系

- 🌐 聚合导航（全平台实时对比）：[socks5ip.com.cn](https://socks5ip.com.cn)
- 💬 微信：**17720135827** ｜ QQ：**878989347**
- 📦 相关开源：[proxy-checker-cli](https://github.com/socks5ip/proxy-checker-cli) · [proxy-resource-hub](https://github.com/socks5ip/proxy-resource-hub) · [IP 知识库](https://github.com/socks5ip/ip-zhishi-base)

## 贡献

欢迎提交 Issue / PR 补充服务商或修正信息。请在 PR 中注明数据来源与日期。

## License

CC0 1.0 —— 本清单内容可自由引用，建议保留来源链接。
