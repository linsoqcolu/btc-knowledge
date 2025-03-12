# DMIT 香港 Tier 1 HKG.T1.WEE 测评

本次测试的是 DMIT 香港机房，套餐为 HKG.T1.WEE，配置为 1核 CPU、1GB 内存、20GB SSD 硬盘、单向 1TB 流量，带宽可达 4Gbps。

---

DMIT 成立于 2018年，由美籍华人创立（ASN：AS906/AS54574），主营业务包括中国香港、美国洛杉矶以及日本东京的独立服务器和 KVM VPS。值得一提的是，DMIT 也是搬瓦工部分机房的上游服务商。凭借其技术优势，据传从不超售，线路稳定表现出色。支付方式支持支付宝、微信和 PayPal，且提供中文客服。

👉 [【推荐收藏】2025年 DMIT 最新优惠活动整理汇总 - 每日更新可用优惠套餐](https://bit.ly/dmit_coupon)

---

## 性能测试结果

### 基础信息（Bench/SuperBench）

plaintext
CPU Model          : AMD EPYC 7402P 24-Core Processor
CPU Cores          : 1 @ 2794.748 MHz
CPU Cache          : 512 KB
AES-NI             : ✓ Enabled
VM-x/AMD-V         : ✗ Disabled
Total Disk         : 20.6 GB (3.6 GB Used)
Total Mem          : 960.7 MB (261.5 MB Used)
Total Swap         : 1024.0 MB (0 Used)
System uptime      : 0 days, 0 hour 12 min
Load average       : 0.00, 0.05, 0.06
OS                 : Debian GNU/Linux 12
Arch               : x86_64 (64 Bit)
Kernel             : 6.1.0-21-amd64
TCP CC             : bbr
Virtualization     : KVM
IPv4/IPv6          : ✓ Online / ✓ Online
Organization       : AS906 DMIT Cloud Services
Location           : Hong Kong / HK
Region             : Hong Kong

----------------------------------------------------------------------
Disk I/O Speed (Average) : 534.3 MB/s
Speedtest.net            : Upload Speed 4273.07 Mbps / Download Speed 4022.95 Mbps / Latency 0.27 ms
Shanghai CU              : Upload Speed 87.18 Mbps  / Download Speed 772.01 Mbps  / Latency 329.35 ms
Singapore SG             : Upload Speed 855.04 Mbps / Download Speed 1740.23 Mbps / Latency 37.26 ms
Tokyo JP                 : Upload Speed 1784.45 Mbps / Download Speed 2620.58 Mbps / Latency 51.35 ms


DMIT 香港机房的硬盘 I/O 表现优异，读取速度超过 500MB/s，对于 I/O 密集型应用有良好的支持。同时，香港机房的网络性能在国际线路中表现出色，延迟和带宽都非常优秀。

---

### 国际网络测速（单线程）

针对主要国际节点测试的下载性能如下：

plaintext
Leaseweb, HongKong, CN   : Download Speed 2791.29 Mbps / Latency 7.480 ms
Hinet, Taiwan            : Download Speed 1485.56 Mbps / Latency 24.450 ms
Linode, Tokyo, JP        : Download Speed 337.28 Mbps  / Latency 54.978 ms
Vultr, Seoul, KR         : Download Speed 519.60 Mbps  / Latency 85.258 ms


香港机房对亚洲地区的网络优化尤为明显，尤其是对台湾、日本等邻近地区的节点，网络延迟极低，非常适合需要亚洲访问的场景。

---

## 套餐推荐

### 套餐配置

- **HKG.T1.WEE**：1 核 CPU / 1 GB 内存 / 20 GB SSD / 单向流量 1000 GB/月 / 1 IPv4 & 1 IPv6 /64，价格 $36.9/年。
- **HKG.T1.MINI**：1 核 CPU / 1 GB 内存 / 20 GB SSD / 单向流量 2000 GB/月 / 1 IPv4 & 1 IPv6 /64，价格 $6.9/月。
- **HKG.T1.STARTER**：1 核 CPU / 2 GB 内存 / 40 GB SSD / 单向流量 4000 GB/月 / 1 IPv4 & 1 IPv6 /64，价格 $12.9/月。
- **HKG.T1.PRO**：2 核 CPU / 2 GB 内存 / 60 GB SSD / 单向流量 8000 GB/月 / 1 IPv4 & 1 IPv6 /64，价格 $21.9/月。

所有套餐均支持香港国际优化线路。在套餐中选择 **Hong Kong** - **Tier 1** 时可以获取详细列表。

**优惠码**：
`T1-WEE-CHRISTMAS-2024-ANNUALLY-10OFF` - 仅适用于 T1.WEE 套餐年付9折优惠。

---

## 测评总结

DMIT 香港机房采用国际线路优化，延迟表现可圈可点。测试结果显示，电信平均延迟 783ms（低至 147ms），移动延迟较低，平均仅 52ms，适合对亚洲网络访问速度有高要求的用户。

适用场景如下：
- 追求国际连接稳定性。
- 不优先考虑 IP 质量或流媒体解锁需求。

总体而言，DMIT 提供了一系列高性价比方案，适合针对国际流量的场景需求。