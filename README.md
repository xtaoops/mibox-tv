# mibox-tv 直播源

给小米盒子 4S Max (MDZ-30-AA) 用的精选直播源。

- `live_all.m3u` — **1236 个逐段验证可播的频道**，按「地区·类型」分组（美国 / 加拿大 / 中国 / 香港 / 国际）
- `fongmi_config.json` — FongMi TV 直播配置

验证方式：沿 HLS 链（主清单 → 子清单 → 媒体分片）真实下载 >1KB 才计入，只返回 200 的空壳源全部剔除。
频道来源：iptv-org 公开目录 + gaotianliuyun/gao 中国源。
