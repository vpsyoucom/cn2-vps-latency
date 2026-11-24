# CN2 VPS 延迟数据大全（2026 年 11 月）

本仓库整理 2026 年 11 月的 CN2 VPS 延迟与丢包快照，方便对照选购和做后续处理。厂商、节点、IP、延迟、丢包和库存按来源原样收录。

- 数据来源：[VPSYOU CN2 VPS 延迟监控首页](https://vpsyou.com/zh)（覆盖 13 家厂商、27 个全球 CN2 测试节点）
- 探测口径：广东单点 IPv4 ICMP 探测，每 30 秒 5 包，按小时汇总（至少延后 1 小时）
- 数据截至：**2026 年 11 月 24 日 07:00（UTC+8，北京时间/香港时间）**
- 快照抓取时间：2026-11-24 08:20（UTC+8）
- 机器可读副本：[data/2026-11-24-cn2-latency.csv](data/2026-11-24-cn2-latency.csv)（UTF-8，无 BOM）

## 自行测试：路由追踪与逐跳地图

想自己测试链路，请访问 **[VPSYOU CN2 路由追踪与逐跳地图](https://vpsyou.com/zh/cn2-traceroute)**。

在页面上可以选择运营商探针（如中国电信等），输入任意公网 IPv4/IPv6，或一键选择站内 CN2 测试 IP，实时执行去程路由追踪（Traceroute / MTR），在地图和逐跳表中查看每跳 IP、估算地理位置、ASN 归属与往返延迟（RTT），并支持分享结果。对照区还提供广州电信 CN2 GIA、上海联通 CUII、台山移动 CMIN2 到洛杉矶 DC6 `162.244.241.102` 的三网对比参考。

## 近 24 小时 CN2 VPS 延迟与丢包总表（首页默认视图）

统计窗口：2026-11-23 07:00 至 2026-11-24 07:00（UTC+8），共 24 个整点小时，每节点发包 14,355 次。

顺序与首页默认视图一致：地区依次为美国、日本、香港、新加坡、德国、英国、俄罗斯、韩国、马来西亚，同一地区内按平均延迟从低到高。

| 序号 | 厂商 | 节点 | 测试 IP | 平均延迟 | 丢包率 | 库存 |
| ---: | --- | --- | --- | ---: | ---: | --- |
| 1 | IMIDC | US 洛杉矶 CN2 GIA | `103.141.1.156` | 147.8 ms | 0.2% | 待确认 |
| 2 | HostDare | US 洛杉矶 CN2 GIA | `185.186.146.8` | 161.8 ms | 7.7% | 有货 |
| 3 | NoSla Cloud | US 圣何塞 Premium | `104.245.12.188` | 163.2 ms | 0% | 待确认 |
| 4 | DMIT | US 洛杉矶 Pro | `179.255.100.100` | 163.8 ms | 0% | 待确认 |
| 5 | DediOne | US 洛杉矶 CN2 GIA | `77.73.8.1` | 165.3 ms | 0.1% | 有货 |
| 6 | BandwagonHost | US 洛杉矶 DC6 | `162.244.241.102` | 169.1 ms | 0% | 待确认 |
| 7 | Axion | US 洛杉矶 Enterprise CN2 | `107.148.84.133` | 170.2 ms | 1.3% | 暂无匹配 |
| 8 | Axion | US 西雅图 Enterprise CN2 | `104.219.211.5` | 171 ms | 1.2% | 暂无匹配 |
| 9 | AkkoCloud | US 圣何塞 CN2 GIA | `104.249.172.5` | 172.6 ms | 0% | 待确认 |
| 10 | Axion | US 圣何塞 Enterprise CN2 | `104.233.147.13` | 173.3 ms | 1% | 暂无匹配 |
| 11 | DMIT | JP 东京 Pro | `191.222.210.210` | 53.5 ms | 0.5% | 待确认 |
| 12 | V.PS | JP 东京 Premium | `45.94.40.13` | 59.8 ms | 1.3% | 待确认 |
| 13 | GigsGigsCloud | JP 东京 CN Premium | `202.144.194.49` | 62.5 ms | 1.7% | 待确认 |
| 14 | Axion | JP 东京 Enterprise CN2 | `104.233.219.12` | 63.8 ms | 0.5% | 暂无匹配 |
| 15 | NoSla Cloud | HK 香港 Standard | `38.76.214.1` | 7.9 ms | 0.7% | 暂无匹配 |
| 16 | HostKVM | HK 香港 China Premium | `149.104.7.77` | 10.9 ms | 0.3% | 待确认 |
| 17 | DMIT | HK 香港 Pro | `191.222.216.216` | 11.1 ms | 0% | 待确认 |
| 18 | IMIDC | HK 香港 CN2 GIA | `5.180.96.134` | 11.3 ms | 1.3% | 待确认 |
| 19 | Server.HK | HK 香港 CN2 GIA | `156.224.19.1` | 16.4 ms | 1.1% | 待确认 |
| 20 | GreenCloudVPS | SG 新加坡 Premium | `45.135.43.11` | 46.3 ms | 0% | 缺货 |
| 21 | Axion | DE 法兰克福 Enterprise CN2 | `107.149.202.4` | 172.2 ms | 0% | 暂无匹配 |
| 22 | AkkoCloud | DE 法兰克福 CN2 GIA | `185.217.109.94` | 176.8 ms | 0% | 待确认 |
| 23 | NoSla Cloud | DE 法兰克福 Premium | `45.80.188.66` | 540.2 ms | 15.8% | 待确认 |
| 24 | AkkoCloud | GB 伦敦 CN2 GIA | `185.217.110.10` | 193.4 ms | 0% | 缺货 |
| 25 | IMIDC | RU 莫斯科 CN2 | `45.150.237.34` | 132.5 ms | 0.5% | 待确认 |
| 26 | Axion | KR 首尔 Enterprise CN2 | `107.148.149.1` | 94.7 ms | 0.3% | 暂无匹配 |
| 27 | Axion | MY 吉隆坡 Enterprise CN2 | `104.233.227.1` | 49.9 ms | 0.3% | 暂无匹配 |

## 近 7 天 CN2 VPS 延迟与丢包汇总参考

统计截至 2026-11-24 07:00（UTC+8）。因数据集始于 2026-11-19 晚间/20 日早间，各节点实际含 95 或 105 个有效小时样本。

地区顺序与上一张表相同。同一地区内按近 7 天平均延迟从低到高；延迟相同时沿用来源表的先后。序号是这张表自己的排列，香港 IMIDC 与 DMIT 因此和近 24 小时总表对调。

| 序号 | 厂商 | 节点 | 测试 IP | 平均延迟 | 丢包率 | 有效小时 |
| ---: | --- | --- | --- | ---: | ---: | ---: |
| 1 | IMIDC | US 洛杉矶 CN2 GIA | `103.141.1.156` | 147.8 ms | 0.2% | 105h |
| 2 | HostDare | US 洛杉矶 CN2 GIA | `185.186.146.8` | 161.5 ms | 6.8% | 105h |
| 3 | NoSla Cloud | US 圣何塞 Premium | `104.245.12.188` | 163.2 ms | 0% | 95h |
| 4 | DMIT | US 洛杉矶 Pro | `179.255.100.100` | 163.8 ms | 0% | 95h |
| 5 | DediOne | US 洛杉矶 CN2 GIA | `77.73.8.1` | 165.2 ms | 0.4% | 95h |
| 6 | BandwagonHost | US 洛杉矶 DC6 | `162.244.241.102` | 169 ms | 0% | 105h |
| 7 | Axion | US 洛杉矶 Enterprise CN2 | `107.148.84.133` | 169.9 ms | 0.7% | 95h |
| 8 | Axion | US 西雅图 Enterprise CN2 | `104.219.211.5` | 170.6 ms | 0.6% | 95h |
| 9 | AkkoCloud | US 圣何塞 CN2 GIA | `104.249.172.5` | 172.5 ms | 0% | 105h |
| 10 | Axion | US 圣何塞 Enterprise CN2 | `104.233.147.13` | 172.9 ms | 0.6% | 95h |
| 11 | DMIT | JP 东京 Pro | `191.222.210.210` | 53.7 ms | 0.5% | 105h |
| 12 | V.PS | JP 东京 Premium | `45.94.40.13` | 59.5 ms | 1.1% | 105h |
| 13 | GigsGigsCloud | JP 东京 CN Premium | `202.144.194.49` | 62.1 ms | 2.1% | 105h |
| 14 | Axion | JP 东京 Enterprise CN2 | `104.233.219.12` | 63.9 ms | 0.4% | 95h |
| 15 | NoSla Cloud | HK 香港 Standard | `38.76.214.1` | 7.8 ms | 0.4% | 95h |
| 16 | HostKVM | HK 香港 China Premium | `149.104.7.77` | 11 ms | 0.3% | 105h |
| 17 | IMIDC | HK 香港 CN2 GIA | `5.180.96.134` | 11.1 ms | 0.7% | 95h |
| 18 | DMIT | HK 香港 Pro | `191.222.216.216` | 11.1 ms | 0% | 95h |
| 19 | Server.HK | HK 香港 CN2 GIA | `156.224.19.1` | 14.6 ms | 0.5% | 95h |
| 20 | GreenCloudVPS | SG 新加坡 Premium | `45.135.43.11` | 46.4 ms | 0% | 105h |
| 21 | Axion | DE 法兰克福 Enterprise CN2 | `107.149.202.4` | 171.5 ms | 0% | 95h |
| 22 | AkkoCloud | DE 法兰克福 CN2 GIA | `185.217.109.94` | 176.3 ms | 0% | 95h |
| 23 | NoSla Cloud | DE 法兰克福 Premium | `45.80.188.66` | 468.9 ms | 11.6% | 105h |
| 24 | AkkoCloud | GB 伦敦 CN2 GIA | `185.217.110.10` | 193.4 ms | 1.5% | 95h |
| 25 | IMIDC | RU 莫斯科 CN2 | `45.150.237.34` | 131.3 ms | 0.4% | 95h |
| 26 | Axion | KR 首尔 Enterprise CN2 | `107.148.149.1` | 94.7 ms | 0.3% | 95h |
| 27 | Axion | MY 吉隆坡 Enterprise CN2 | `104.233.227.1` | 48.7 ms | 0.3% | 95h |

## 自行测试：路由追踪与逐跳地图

想自己测试链路，请访问 **[VPSYOU CN2 路由追踪与逐跳地图](https://vpsyou.com/zh/cn2-traceroute)**。

在页面上可以选择运营商探针（如中国电信等），输入任意公网 IPv4/IPv6，或一键选择站内 CN2 测试 IP，实时执行去程路由追踪（Traceroute / MTR），在地图和逐跳表中查看每跳 IP、估算地理位置、ASN 归属与往返延迟（RTT），并支持分享结果。对照区还提供广州电信 CN2 GIA、上海联通 CUII、台山移动 CMIN2 到洛杉矶 DC6 `162.244.241.102` 的三网对比参考。

## 地区简况

这一节只整理上面两张表里的原数。写出的差值，是两个窗口对应原数直接相减。

近 24 小时全表最低延迟是 NoSla Cloud「HK 香港 Standard」（`38.76.214.1`）7.9 ms，丢包 0.7%。最高延迟和最高丢包是同一节点：NoSla Cloud「DE 法兰克福 Premium」（`45.80.188.66`）540.2 ms，丢包 15.8%。丢包第二高的是 HostDare「US 洛杉矶 CN2 GIA」，近 24 小时丢包 7.7%（161.8 ms），近 7 天丢包 6.8%（161.5 ms，105 小时）。

下表按各地区近 24 小时最低延迟从低到高排列。上面的总表仍按首页顺序排列。

| 地区 | 节点数 | 近 24 小时延迟 | 最低延迟节点 | 该地区最高丢包 |
| --- | ---: | --- | --- | --- |
| 香港 | 5 | 7.9 ms 至 16.4 ms | NoSla Cloud「HK 香港 Standard」，7.9 ms | 1.3%（IMIDC「HK 香港 CN2 GIA」） |
| 新加坡 | 1 | 46.3 ms | GreenCloudVPS「SG 新加坡 Premium」，46.3 ms | 0%（GreenCloudVPS「SG 新加坡 Premium」） |
| 马来西亚 | 1 | 49.9 ms | Axion「MY 吉隆坡 Enterprise CN2」，49.9 ms | 0.3%（Axion「MY 吉隆坡 Enterprise CN2」） |
| 日本 | 4 | 53.5 ms 至 63.8 ms | DMIT「JP 东京 Pro」，53.5 ms | 1.7%（GigsGigsCloud「JP 东京 CN Premium」） |
| 韩国 | 1 | 94.7 ms | Axion「KR 首尔 Enterprise CN2」，94.7 ms | 0.3%（Axion「KR 首尔 Enterprise CN2」） |
| 俄罗斯 | 1 | 132.5 ms | IMIDC「RU 莫斯科 CN2」，132.5 ms | 0.5%（IMIDC「RU 莫斯科 CN2」） |
| 美国 | 10 | 147.8 ms 至 173.3 ms | IMIDC「US 洛杉矶 CN2 GIA」，147.8 ms | 7.7%（HostDare「US 洛杉矶 CN2 GIA」） |
| 德国 | 3 | 172.2 ms 至 540.2 ms | Axion「DE 法兰克福 Enterprise CN2」，172.2 ms | 15.8%（NoSla Cloud「DE 法兰克福 Premium」） |
| 英国 | 1 | 193.4 ms | AkkoCloud「GB 伦敦 CN2 GIA」，193.4 ms | 0%（AkkoCloud「GB 伦敦 CN2 GIA」） |

德国近 24 小时三台为：Axion「DE 法兰克福 Enterprise CN2」172.2 ms（丢包 0%）、AkkoCloud「DE 法兰克福 CN2 GIA」176.8 ms（丢包 0%）、NoSla Cloud「DE 法兰克福 Premium」540.2 ms（丢包 15.8%）。美国有 2 台高于德国最低的 172.2 ms：AkkoCloud「US 圣何塞 CN2 GIA」172.6 ms、Axion「US 圣何塞 Enterprise CN2」173.3 ms。英国 AkkoCloud「GB 伦敦 CN2 GIA」193.4 ms，高于德国前两台，低于 NoSla Cloud「DE 法兰克福 Premium」。

同一地区里，两张表的先后只有香港不同：近 24 小时是 DMIT「HK 香港 Pro」11.1 ms 在前、IMIDC「HK 香港 CN2 GIA」11.3 ms 在后；近 7 天这两台都是 11.1 ms，近 7 天表把 IMIDC 排在 DMIT 前面。

近 24 小时与近 7 天的延迟、丢包都相同的有 5 个节点：IMIDC「US 洛杉矶 CN2 GIA」147.8 ms、丢包 0.2%（105 小时）、NoSla Cloud「US 圣何塞 Premium」163.2 ms、丢包 0%（95 小时）、DMIT「US 洛杉矶 Pro」163.8 ms、丢包 0%（95 小时）、DMIT「HK 香港 Pro」11.1 ms、丢包 0%（95 小时）、Axion「KR 首尔 Enterprise CN2」94.7 ms、丢包 0.3%（95 小时）。

近 24 小时与近 7 天相比，延迟相差达到 1 ms，或丢包相差达到 1 个百分点的节点：

- NoSla Cloud「DE 法兰克福 Premium」：近 24 小时 540.2 ms、丢包 15.8%；近 7 天 468.9 ms、丢包 11.6%（105 小时）。近 24 小时延迟高 71.3 ms，丢包高 4.2 个百分点。
- Server.HK「HK 香港 CN2 GIA」：近 24 小时 16.4 ms、丢包 1.1%；近 7 天 14.6 ms、丢包 0.5%（95 小时）。近 24 小时延迟高 1.8 ms，丢包高 0.6 个百分点。
- AkkoCloud「GB 伦敦 CN2 GIA」：近 24 小时 193.4 ms、丢包 0%；近 7 天 193.4 ms、丢包 1.5%（95 小时）。延迟相同，丢包低 1.5 个百分点。
- IMIDC「RU 莫斯科 CN2」：近 24 小时 132.5 ms、丢包 0.5%；近 7 天 131.3 ms、丢包 0.4%（95 小时）。近 24 小时延迟高 1.2 ms，丢包高 0.1 个百分点。
- Axion「MY 吉隆坡 Enterprise CN2」：近 24 小时 49.9 ms、丢包 0.3%；近 7 天 48.7 ms、丢包 0.3%（95 小时）。近 24 小时延迟高 1.2 ms，丢包相同。

近 7 天有效小时为 105 的有 10 个节点，为 95 的有 17 个节点。数据集始于 2026-11-19 晚间/20 日早间，因此有效小时只有这两个数。

近 24 小时库存标记：有货 2 个（HostDare「US 洛杉矶 CN2 GIA」、DediOne「US 洛杉矶 CN2 GIA」），缺货 2 个（GreenCloudVPS「SG 新加坡 Premium」、AkkoCloud「GB 伦敦 CN2 GIA」），暂无匹配 8 个（Axion 全部 7 个节点，以及 NoSla Cloud「HK 香港 Standard」），其余 15 个为待确认。

近 24 小时丢包写成 0% 的有 9 个节点：NoSla Cloud「US 圣何塞 Premium」、DMIT「US 洛杉矶 Pro」、BandwagonHost「US 洛杉矶 DC6」、AkkoCloud「US 圣何塞 CN2 GIA」、DMIT「HK 香港 Pro」、GreenCloudVPS「SG 新加坡 Premium」、Axion「DE 法兰克福 Enterprise CN2」、AkkoCloud「DE 法兰克福 CN2 GIA」、AkkoCloud「GB 伦敦 CN2 GIA」。这里的 0% 是按 1 位小数保留后的结果，窗口内仍可能有极少量丢包，说明见下一节。

## 测量方法与阅读注意

探测只有广东一个点，协议是 IPv4 ICMP：每 30 秒 5 个包，先按小时汇总，页面展示至少比探测时间晚 1 小时。本页数据截至 2026 年 11 月 24 日 07:00（UTC+8），快照在 2026-11-24 08:20（UTC+8）抓取。

- 这是广东单点看到的去程 ICMP 往返。返程路径需要另行验证。
- 丢包率保留到小数点后 1 位。写成 `0%` 时，表示按这一位保留后是 0，窗口里仍可能有极少量丢包。
- 近 24 小时每个节点的发包次数都是 14,355 次。近 7 天的有效样本为 95 或 105 小时，对比时要连「有效小时」一起看。
- 库存是这次快照里的页面标记，取值为有货、缺货、待确认、暂无匹配。套餐此刻能否购买，要到厂商页面另行核实。
- 核验时，GigsGigsCloud 东京节点的 Looking Glass 无法打开。该节点主机名可以解析，测试 IP 对 ICMP 有响应；表中延迟和丢包仍按监控结果原样列出。

## 相关链接

- 实时完整延迟监控榜：[https://vpsyou.com/zh](https://vpsyou.com/zh)
- 自助路由追踪与逐跳地图：[https://vpsyou.com/zh/cn2-traceroute](https://vpsyou.com/zh/cn2-traceroute)
- MCP / CLI / Agent Skill 查询工具：[vpsyoucom/vpsyou-mcp](https://github.com/vpsyoucom/vpsyou-mcp)

## CSV 字段

`data/2026-11-24-cn2-latency.csv` 为 UTF-8 编码，无 BOM，首行是表头，其后 27 行与近 24 小时总表一一对应，按 `rank_24h` 排列。同一 IP 的 7 天指标与第二张表是同一条记录。

| 列名 | 含义 |
| --- | --- |
| `rank_24h` | 近 24 小时首页序号，1 到 27 |
| `provider` | 厂商 |
| `location` | 节点名称，与总表相同 |
| `ip` | 测试 IP |
| `avg_ping_24h_ms` | 近 24 小时平均延迟，单位毫秒。单元格只写数字；来源是整数时，这里也是整数，例如 `171` |
| `loss_24h_pct` | 近 24 小时丢包率，单位为百分数。`0.2` 表示 0.2%，`0` 表示 0%，`1` 表示 1% |
| `stock` | 库存标记：有货、缺货、待确认、暂无匹配 |
| `avg_ping_7d_ms` | 近 7 天平均延迟，单位毫秒。单元格只写数字，整数保持整数，例如 `169`、`11` |
| `loss_7d_pct` | 近 7 天丢包率，单位为百分数，写法和 `loss_24h_pct` 相同 |
| `hours_7d` | 近 7 天有效小时数。`105` 表示 105 小时，`95` 表示 95 小时 |
