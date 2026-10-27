# Bitdsk Miner Archive

Bitdsk 全系矿机的固件归档。**这里只放文件，不放页面。**

- 索引与说明：<https://bitdsk.org/firmware.html>
- 浏览器烧录（S1 / U1 / U2）：<https://bitdsk.github.io/bitdsk-flash/>
- S1 固件源码（MIT）：<https://github.com/bitdsk/Bitdsk-s1-Miner>

## 目录

```
firmware/
├─ n5-series/     N5.Rex / N5.Rexi / D12 / D12-T
├─ n8-series/     N8 / N8-T / N5.Rexi-T
│  └─ blackbox/   BLACKBOX 调试版
├─ u-series/      U1 / U2 的 OTA 单镜像与 UI 主题背景
├─ legacy/        停产型号：n_update n_www n_miner d_update d_www d_miner d9 n5
├─ tools/         PC 批量管理工具
└─ hardware/      PCB Gerber
```

S1 / U1 / U2 的**整机烧录包**不在这里，在
[bitdsk-flash](https://github.com/bitdsk/bitdsk-flash) 仓库。

## 怎么下载

主站 <https://bitdsk.org/firmware.html> 是索引页，每个文件都列了大小和 SHA256。
也可以直接用 jsDelivr：

```
https://cdn.jsdelivr.net/gh/bitdsk/Bitdsk_Miner_Archive@main/firmware/n5-series/all.3.3_sec.zip
```

## 说明

- **版本日期是迁移来的，可能不准。** 版本号准确，但旁边的日期取自原 WordPress
  站的下拉表格，可能差几天。
- 文件名保持原样，没有改名，方便和旧链接、SHA256 记录对上。
- 这些文件只做归档分发，不在本仓库维护源码。
