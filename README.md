# Mi Box TV：公开直播精选

面向小米盒子 4S Max 的 TVBox / FongMi 配置。默认只发布可追溯到播出机构或其 CDN、且在 2026-11-14 的当前网络中能返回 HLS 清单的地址；不含账号、代理、爬虫或绕过地区限制的配置。

## 一键地址

| 用途 | 地址 |
| --- | --- |
| TVBox 配置 | `https://raw.githubusercontent.com/xtaoops/mibox-tv/master/tvbox_config.json` |
| FongMi 配置 | `https://raw.githubusercontent.com/xtaoops/mibox-tv/master/fongmi_config.json` |
| 通用 M3U 直播清单 | `https://raw.githubusercontent.com/xtaoops/mibox-tv/master/public_broadcasters.m3u` |

TVBox 中填入“TVBox 配置”地址即可；支持 M3U 的其他播放器填“通用 M3U 直播清单”。

## 当前频道

- 国际新闻：BBC World Service（英语音频）、DW English、DW Deutsch、France 24 English、France 24 Français、Bloomberg TV、TRT World、CGTN English
- 加拿大·卡尔加里：CityNews Calgary
- 香港：RTHK TV 31

播出权会因地点或时段变化。BBC 条目是 BBC World Service 音频流；CBC Calgary（404）、TaiwanPlus（400）和 Al Jazeera English（当前网络无法解析）未纳入。

## 旧清单

`live_all.m3u` 为仓库原有文件，含大量未经逐一授权审查的第三方地址，保留供历史参考，但不作为默认配置，也不会在本项目中继续扩充。
