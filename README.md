# TopFreeProxies
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/alanbobs999/topfreeproxies/sub_merge?label=sub_merge)](https://github.com/alanbobs999/TopFreeProxies/actions/workflows/sub_merge.yml) 

![Watchers](https://img.shields.io/github/watchers/alanbobs999/topfreeproxies) ![Stars](https://img.shields.io/github/stars/alanbobs999/topfreeproxies) ![Forks](https://img.shields.io/github/forks/alanbobs999/topfreeproxies) ![Vistors](https://visitor-badge.laobi.icu/badge?page_id=alanbobs999.topfreeproxies) ![LICENSE](https://img.shields.io/badge/license-CC%20BY--SA%204.0-green.svg)

[仓库介绍](https://github.com/alanbobs999/TopFreeProxies#仓库介绍) | [使用方法](https://github.com/alanbobs999/TopFreeProxies#使用方法) | [节点信息](https://github.com/alanbobs999/TopFreeProxies#节点信息) | [软件推荐](https://github.com/alanbobs999/TopFreeProxies#客户端选择) | [机场推荐](https://github.com/alanbobs999/TopFreeProxies#机场推荐) | [仓库声明](https://github.com/alanbobs999/TopFreeProxies#仓库声明)

## 仓库介绍
本仓库自动化功能全部基于 `GitHub Actions` 实现，如果有需要可以自行 Fork 实现个性化需求。

对网络上各免费节点池及博主分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。所筛选的节点链接在仓库 `./sub/sub_list.json` 文件中，其中大部分为其他 `GitHub` 仓库链接，如果大家有好的订阅链接欢迎提交 PR ，这些链接包含的所有节点会合并在仓库 `./sub/sub_merge.txt` 中。

测速筛选后的节点订阅文件在仓库根目录 `Eterniy`(Base64) 和 `Eternity.yml`(Clash)。同时在仓库的 `./update` 中保留了原始节点链接的的记录。

测速功能使用 [LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest) 在 `GitHub Actions` 环境下实现，所以美国节点较多，不能很好代表国内网络环境下节点可用性，目前正在解决这一问题。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择`Clash`, `Shadowrocket`之类能自动切换低延迟节点的客户端。

## 使用方法
将以下订阅链接导入相应客户端即可。链接中大部分为 SS 协议节点，少量 Vmess, Trojan ,SSR 协议节点，建议选择协议支持完整的客户端。

- [多协议Base64编码](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/Eternity)
- [Clash](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/Eternity.yml)

另有国内加速链接：

- [多协议Base64编码](https://fastly.jsdelivr.net/gh/alanbobs999/TopFreeProxies@master/Eternity)
- [Clash](https://fastly.jsdelivr.net/gh/alanbobs999/TopFreeProxies@master/Eternity.yml)

>`Clash`链接所使用的配置在仓库`./update/provider/`中，有相应配置文件和以国家分类的`proxy-provider`。
>
>需要其它配置可使用订阅转换工具自行转换。
>自用在线订阅转换网址：[sub-web-modify](https://sub.v1.mk/)

## 节点信息
### 高速节点
高速节点数量: `99`
<details>
  <summary>展开复制节点</summary>

    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MTgxMDUiLCJhZGQiOiJ1czAzLmdvZ29nb28uY3lvdSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiZGI1ZDFhYTMtOTA4Yi00NGQxLWJlMGEtNGU2YThkNGU0Y2RhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9nbyIsImhvc3QiOiJ1czAzLmdvZ29nb28uY3lvdSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA4NCIsImFkZCI6Imllc2VpMWVpLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJpZXNlaTFlaS5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA0MCIsImFkZCI6IjE5Mi4xODYuMTI5LjY2IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1idWZmYWxvLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MTQ1NTkiLCJhZGQiOiJ1czAzLmdvZ29nb28uY3lvdSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiZGI1ZDFhYTMtOTA4Yi00NGQxLWJlMGEtNGU2YThkNGU0Y2RhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9nbyIsImhvc3QiOiJ1czAzLmdvZ29nb28uY3lvdSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA4NSIsImFkZCI6IjIwOC45OC40OC4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6Imllc2VpMWVpLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA0OSIsImFkZCI6IjE5Mi45Ni4yMDQuMjUwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2MiIsImFkZCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2Etd2FzaGluZ3Rvbi5sdnVmdC5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA0MSIsImFkZCI6InVzYS1idWZmYWxvLmx2dWZ0LmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2EtYnVmZmFsby5sdnVmdC5jb20iLCJ0bHMiOiJ0bHMifQ==
    ss://YWVzLTI1Ni1jZmI6NDQxNTkzNDI5NQ@91.193.6.66:50004#CA_209
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2MCIsImFkZCI6IjE5Mi4xODYuMTI5LjY2IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1idWZmYWxvLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KOe7v+WktOWklue9kembhuWboikoUHVibGljKSIsImFkZCI6InVzMDIuZ29nb2dvby5jeW91IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJkYjVkMWFhMy05MDhiLTQ0ZDEtYmUwYS00ZTZhOGQ0ZTRjZGEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2dvIiwiaG9zdCI6InVzMDIuZ29nb2dvby5jeW91IiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA0NyIsImFkZCI6IjIwOC45OC40OC4yIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6Imllc2VpMWVpLmNvbSIsInRscyI6InRscyJ9
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20039
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%205%20%E2%86%92%20t.me%2Fs%2FSCINV
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%204%20%E2%86%92%20t.me%2Fs%2FSCINV
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%204%20%E2%86%92%20t.me%2Fs%2FSCINV
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:810#%F0%9F%87%A8%F0%9F%87%A6%20github.com%2Ffreefq%20-%20%E5%8A%A0%E6%8B%BF%E5%A4%A7%20%202
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:810#%F0%9F%87%A8%F0%9F%87%A6%20github.com%2Ffreefq%20-%20%E5%8A%A0%E6%8B%BF%E5%A4%A7%20%202
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20057
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggUmVsYXlf8J+HuvCfh7hVUy3wn4e68J+HuFVTXzc0IiwiYWRkIjoiYndnMi5ndXNoaWRhd2FuZy5jYyIsInBvcnQiOiI1NzUzOSIsInR5cGUiOiJub25lIiwiaWQiOiJmY2Y3MjAyYy1iZDFhLTQ0ZTktYTI1ZS1iZjE1MmY2ZTVjMTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiYndnMi5ndXNoaWRhd2FuZy5jYyIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:810#%F0%9F%87%A8%F0%9F%87%A6%20github.com%2Ffreefq%20-%20%E5%8A%A0%E6%8B%BF%E5%A4%A7%20%202
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%28%E7%BB%BF%E5%A4%B4%E5%A4%96%E7%BD%91%E9%9B%86%E5%9B%A2%29%28Public%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqvCfh7og5qyn5rSyKOayueeuoTrnoLTop6PotYTmupDlkJsyLjApIiwiYWRkIjoiMTA0LjE2LjE5OS4xIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI0NTIwMmIzNS1lYWUzLTRlMzQtODRhZi1iNDIwNjBmYjkxODciLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2ZxbG92d3MiLCJob3N0IjoiaW9pLnh4aW9peHgudGsiLCJ0bHMiOiJ0bHMifQ==
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s1.hazz.win:12340?allowInsecure=1&sni=s1.hazz.win#US_2
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s1.hazz.win:12340?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%205%20%E2%86%92%20t.me%2Fs%2FSCINV
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20042
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s2.hazz.win:12340?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%207%20%E2%86%92%20t.me%2Fs%2FSCINV
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%203%20%E2%86%92%20t.me%2Fs%2FSCINV
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:810#%F0%9F%87%A8%F0%9F%87%A6%20_CA_%E5%8A%A0%E6%8B%BF%E5%A4%A7_2
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDAzOSIsImFkZCI6IjE5Mi4xODYuMTI5LjY2IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1idWZmYWxvLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%206%20%E2%86%92%20TG%40SCINV
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggdjJyYXlmcmVlLmV1Lm9yZyAtIOe+juWbvSAgNiIsImFkZCI6InRhb2Jhby5iYWJhemh1amkuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIzNjcxMmJlOC1mMmZmLTQ4NzUtOGM2Ny05NWVmZDY2YWM5OTQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2RpZGkiLCJob3N0IjoidGFvYmFvLmJhYmF6aHVqaS5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MTQxMDciLCJhZGQiOiJ1czAyLmdvZ29nb28uY3lvdSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiZGI1ZDFhYTMtOTA4Yi00NGQxLWJlMGEtNGU2YThkNGU0Y2RhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9nbyIsImhvc3QiOiJ1czAyLmdvZ29nb28uY3lvdSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2OSIsImFkZCI6IjEwNC4yMjQuMTg4LjI5IiwicG9ydCI6IjM4MjI2IiwidHlwZSI6Im5vbmUiLCJpZCI6IjkyOTlmYjc4LTI5MGMtNGFhZC1iZWZiLTAxMzBjMDc0YTYyMiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiL3dzIiwiaG9zdCI6Imx2dWZ0LmNvbSIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:810#%F0%9F%87%A8%F0%9F%87%A6%20v2rayfree.eu.org%20-%20%E5%8A%A0%E6%8B%BF%E5%A4%A7%20%202
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s3.hazz.win:12340?allowInsecure=1&sni=s3.hazz.win#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20028
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s1.hazz.win:12340?allowInsecure=1&sni=s1.hazz.win#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20021
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA4OSIsImFkZCI6ImJ3ZzIuZ3VzaGlkYXdhbmcuY2MiLCJwb3J0IjoiNTc1MzkiLCJ0eXBlIjoibm9uZSIsImlkIjoiZmNmNzIwMmMtYmQxYS00NGU5LWEyNWUtYmYxNTJmNmU1YzExIiwiYWlkIjoiMCIsIm5ldCI6InRjcCIsInBhdGgiOiIvNTNmOWFkMC8iLCJob3N0IjoiYndnMi5ndXNoaWRhd2FuZy5jYyIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:810#%F0%9F%87%A8%F0%9F%87%A6%20%E5%8A%A0%E6%8B%BF%E5%A4%A7%20004
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s1.hazz.win:12340?allowInsecure=1&sni=s1.hazz.win#US_2
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s1.hazz.win:12340?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20039
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s1.hazz.win:12340?allowInsecure=1&sni=edge.apple.com#%E8%BF%99%E6%98%AF%E6%95%99%E7%A8%8B%E8%B5%A0%E9%80%81%E5%85%8D%E8%B4%B9%E8%8A%82%E7%82%B9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDAzOCIsImFkZCI6InVzYS1idWZmYWxvLmx2dWZ0LmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1c2EtYnVmZmFsby5sdnVmdC5jb20iLCJ0bHMiOiJ0bHMifQ==
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s1.hazz.win:12340?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20036
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggUmVsYXlf8J+HuvCfh7hVUy3wn4e68J+HuFVTXzY1IiwiYWRkIjoidXNhLWRhbGxhcy5sdnVmdC5jb20iLCJwb3J0IjoiNDQzIiwidHlwZSI6Im5vbmUiLCJpZCI6ImFiYTUwZGQ0LTU0ODQtM2IwNS1iMTRhLTQ2NjFjYWY4NjJkNSIsImFpZCI6IjQiLCJuZXQiOiJ3cyIsInBhdGgiOiIvd3MiLCJob3N0IjoidXNhLWRhbGxhcy5sdnVmdC5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm70gIDYiLCJhZGQiOiJ0YW9iYW8uYmFiYXpodWppLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzY3MTJiZTgtZjJmZi00ODc1LThjNjctOTVlZmQ2NmFjOTk0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kaWRpIiwiaG9zdCI6InRhb2Jhby5iYWJhemh1amkuY29tIiwidGxzIjoidGxzIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:800#%F0%9F%87%A8%F0%9F%87%A6%20github.com%2Ffreefq%20-%20%E5%8A%A0%E6%8B%BF%E5%A4%A7%20%204
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:800#%F0%9F%87%A8%F0%9F%87%A6%20%E5%8A%A0%E6%8B%BF%E5%A4%A7%20006
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:803#%F0%9F%87%A8%F0%9F%87%A6%20_CA_%E5%8A%A0%E6%8B%BF%E5%A4%A7
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:800#%F0%9F%87%A8%F0%9F%87%A6%20github.com%2Ffreefq%20-%20%E5%8A%A0%E6%8B%BF%E5%A4%A7%20%204
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:800#%F0%9F%87%A8%F0%9F%87%A6%20github.com%2Ffreefq%20-%20%E5%8A%A0%E6%8B%BF%E5%A4%A7%20%204
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggdjJyYXlmcmVlLmV1Lm9yZyAtIOe+juWbveWKoOWIqeemj+WwvOS6muW3nua0m+adieeftklUN+e9kee7nCA3IiwiYWRkIjoiYndnMi5ndXNoaWRhd2FuZy5jYyIsInBvcnQiOiI1NzUzOSIsInR5cGUiOiJub25lIiwiaWQiOiJmY2Y3MjAyYy1iZDFhLTQ0ZTktYTI1ZS1iZjE1MmY2ZTVjMTEiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii81M2Y5YWQwLyIsImhvc3QiOiJid2cyLmd1c2hpZGF3YW5nLmNjIiwidGxzIjoiIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:800#%F0%9F%87%A8%F0%9F%87%A6%20v2rayfree.eu.org%20-%20%E5%8A%A0%E6%8B%BF%E5%A4%A7%20%204
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpHIXlCd1BXSDNWYW8@72.140.224.195:800#%F0%9F%87%A8%F0%9F%87%A6%20_CA_%E5%8A%A0%E6%8B%BF%E5%A4%A7_4
    vmess://eyJ2IjoiMiIsInBzIjoi6L+Z5Lqb6IqC54K55Y+q6IO95aSH55So5oiW6ICF6Ziy5q2i5aSx6IGU77yM6Jm954S26LSo6YeP5bm25LiN5piv5b6I5aW977yM5Lmf6K+35L2O6LCD5L2/55SoOikiLCJhZGQiOiJ0YW9iYW8uYmFiYXpodWppLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzY3MTJiZTgtZjJmZi00ODc1LThjNjctOTVlZmQ2NmFjOTk0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kaWRpIiwiaG9zdCI6InRhb2Jhby5iYWJhemh1amkuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7ggZ2l0aHViLmNvbS9mcmVlZnEgLSDnvo7lm70gIDYiLCJhZGQiOiJ0YW9iYW8uYmFiYXpodWppLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzY3MTJiZTgtZjJmZi00ODc1LThjNjctOTVlZmQ2NmFjOTk0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kaWRpIiwiaG9zdCI6InRhb2Jhby5iYWJhemh1amkuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA0OCIsImFkZCI6Imllc2VpMWVpLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJpZXNlaTFlaS5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MTgxMDYiLCJhZGQiOiJ1czAyLmdvZ29nb28uY3lvdSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiZGI1ZDFhYTMtOTA4Yi00NGQxLWJlMGEtNGU2YThkNGU0Y2RhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9nbyIsImhvc3QiOiJ1czAyLmdvZ29nb28uY3lvdSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiVVNfMTg3MCIsImFkZCI6IjEwNC4yMjQuMTg4LjI5IiwicG9ydCI6IjM4MjI2IiwidHlwZSI6Im5vbmUiLCJpZCI6IjkyOTlmYjc4LTI5MGMtNGFhZC1iZWZiLTAxMzBjMDc0YTYyMiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s3.hazz.win:12340?allowInsecure=1&sni=s3.hazz.win#US_1
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20033
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20034
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MTgxMDgiLCJhZGQiOiJ0YW9iYW8uYmFiYXpodWppLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzY3MTJiZTgtZjJmZi00ODc1LThjNjctOTVlZmQ2NmFjOTk0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kaWRpIiwiaG9zdCI6InRhb2Jhby5iYWJhemh1amkuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA1MiIsImFkZCI6IjE1MC4yMzAuNDEuOSIsInBvcnQiOiIyMzI5MiIsInR5cGUiOiJub25lIiwiaWQiOiI5NTZjNmMyZi1iZjU0LTRiODctZmFmZC00Yjc2N2NhMTI3NTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMzQuMjE1LjEzMC4xODYiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9KOayueeuoTrnoLTop6PotYTmupDlkJsyLjApIiwiYWRkIjoiMTUwLjIzMC40MS45IiwicG9ydCI6IjIzMjkyIiwidHlwZSI6Im5vbmUiLCJpZCI6Ijk1NmM2YzJmLWJmNTQtNGI4Ny1mYWZkLTRiNzY3Y2ExMjc1MCIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiLyIsImhvc3QiOiIxNTAuMjMwLjQxLjkiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDAwMyIsImFkZCI6IjEyOS4xNTkuMzMuMTk5IiwicG9ydCI6IjQ1MzI4IiwidHlwZSI6Im5vbmUiLCJpZCI6Ijg0MmMzM2ZmLTMxYjUtNDEwYy1hOTZlLTBjYjUyYTk5YTZkYSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IjEyOS4xNTkuMzMuMTk5IiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MTg1MTIiLCJhZGQiOiIxNTAuMjMwLjQzLjEwNiIsInBvcnQiOiI1NDgyOSIsInR5cGUiOiJub25lIiwiaWQiOiJmMmI1YzNmZi04NmM3LTRlZmEtODMxZi1mZjBmY2Q3NjU2YTUiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9pbmRleCIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA0MSIsImFkZCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    trojan://58d32c66-43b1-4561-9951-d87c9123774e@jgwld4.gaox.ml:443?allowInsecure=1#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD%20007
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrPCfh6cg6Iux5Zu9XzA3MTgwMDIiLCJhZGQiOiJ1azAxLnhpYW9xaTk5LmNmIiwicG9ydCI6IjEwMjIiLCJ0eXBlIjoibm9uZSIsImlkIjoiZmJmODEzYmYtOGRmNy00NzI5LThlOTQtNjY3YjE3NTQ0ZTBmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoidWswMS54aWFvcWk5OS5jZiIsInRscyI6IiJ9
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%28%E7%BB%BF%E5%A4%B4%E5%A4%96%E7%BD%91%E9%9B%86%E5%9B%A2%29%28Public%29
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrPCfh6cg6Iux5Zu9IDAxMCIsImFkZCI6InVrMDEueGlhb3FpOTkuY2YiLCJwb3J0IjoiMTAyMiIsInR5cGUiOiJub25lIiwiaWQiOiJmYmY4MTNiZi04ZGY3LTQ3MjktOGU5NC02NjdiMTc1NDRlMGYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJ1azAxLnhpYW9xaTk5LmNmIiwidGxzIjoiIn0=
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20032
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrPCfh6cg6Iux5Zu9XzA3MTgwMDciLCJhZGQiOiJ1azAxLnhpYW9xaTk5LmNmIiwicG9ydCI6IjEwMjIiLCJ0eXBlIjoiYXV0byIsImlkIjoiZmJmODEzYmYtOGRmNy00NzI5LThlOTQtNjY3YjE3NTQ0ZTBmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoidWswMS54aWFvcWk5OS5jZiIsInRscyI6IiJ9
    trojan://58d32c66-43b1-4561-9951-d87c9123774e@jgwld4.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%206%20%E2%86%92%20t.me%2Fs%2FSCINV
    trojan://f39bd244-f5fe-415c-8b98-a1e5250bf178@fhcarm2.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%203%20%E2%86%92%20t.me%2Fs%2FSCINV
    trojan://4863e1b2-ec2f-4c71-b862-ce533028e57e@trus.moonfree.top:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%2012%20%E2%86%92%20t.me%2Fs%2FSCINV
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrPCfh6cg6Iux5Zu9XzA3MTgwMDYiLCJhZGQiOiJ1azAxLnhpYW9xaTk5LmNmIiwicG9ydCI6IjEwMjIiLCJ0eXBlIjoiYXV0byIsImlkIjoiZmJmODEzYmYtOGRmNy00NzI5LThlOTQtNjY3YjE3NTQ0ZTBmIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoidWswMS54aWFvcWk5OS5jZiIsInRscyI6IiJ9
    trojan://dfbf0d67-f03d-4184-a224-c2d64a571f99@s1.hazz.win:12340?allowInsecure=1&sni=s1.hazz.win#US_2
    trojan://02e653c9-7c93-46a9-999d-11834bd0c577@jgwld1.gaox.ml:443?allowInsecure=1#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD%20004
    trojan://94afcc56-cc1c-4cd4-8c82-1215cd052795@youtube-bai-piao-wang-zhe.nl.884899.cf:41196?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20022
    trojan://94afcc56-cc1c-4cd4-8c82-1215cd052795@youtube-bai-piao-wang-zhe.nl.884899.cf:41196?allowInsecure=1&sni=youtube-bai-piao-wang-zhe.nl.884899.cf#%F0%9F%87%B3%F0%9F%87%B1%20TG%40moneyflychat%20%20%E4%B8%AD%E8%BD%AC%E8%8A%82%E7%82%B9%F0%9F%87%B3%F0%9F%87%B1NL-%F0%9F%87%B3%F0%9F%87%B1NL_678%20%7C%207.87Mb
    trojan://94afcc56-cc1c-4cd4-8c82-1215cd052795@youtube-bai-piao-wang-zhe.nl.884899.cf:41196?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%2015%20%E2%86%92%20t.me%2Fs%2FSCINV
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HrPCfh6cg6Iux5Zu9IDAwOSIsImFkZCI6IjE0Ni43MC40Ni42OCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJ1ay1tYW5jaGVzdGVyLmVpdzJlZW1vLmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA0MyIsImFkZCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    trojan://4863e1b2-ec2f-4c71-b862-ce533028e57e@trus.moonfree.top:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20US%201%20%E2%86%92%20t.me%2Fs%2FSCINV
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9XzA3MTgxMDYiLCJhZGQiOiJ1czAyLmdvZ29nb28uY3lvdSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiZGI1ZDFhYTMtOTA4Yi00NGQxLWJlMGEtNGU2YThkNGU0Y2RhIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9nbyIsImhvc3QiOiJ1czAyLmdvZ29nb28uY3lvdSIsInRscyI6InRscyJ9
    trojan://05742120-ce23-4cc8-88f5-6d221ce45bf4@fhcarm1.gaox.ml:443?allowInsecure=1#%F0%9F%87%BA%F0%9F%87%B8%20%E7%BE%8E%E5%9B%BD%20050
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA3NSIsImFkZCI6IjE5Mi45Ni4yMDQuMjUwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2MSIsImFkZCI6IjE1MC4yMzAuNDEuOSIsInBvcnQiOiIyMzI5MiIsInR5cGUiOiJub25lIiwiaWQiOiI5NTZjNmMyZi1iZjU0LTRiODctZmFmZC00Yjc2N2NhMTI3NTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii9pbmRleCIsImhvc3QiOiI4NzMxODcwNi13cy52YS5odXlhLmNvbSIsInRscyI6IiJ9
    trojan://d7fd8aaa-4581-4281-80aa-4b63e5e1f157@jgwld2.gaox.ml:443?allowInsecure=1#%F0%9F%87%AC%F0%9F%87%A7%20%E8%8B%B1%E5%9B%BD%20005
    vmess://eyJ2IjoiMiIsInBzIjoiUG9vbF/wn4e68J+HuFVTXzY5IiwiYWRkIjoiNDUuMzUuODQuMTYyIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS1kYWxsYXMubHZ1ZnQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqfCfh6og5b635Zu9XzA3MTgwMDMiLCJhZGQiOiIxNDYuMC40Mi44NyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJnZXJtYW55LWR1c3NlbGRvcmYubWFoM0hvZXQuY29tIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA2NiIsImFkZCI6IjE5Mi45Ni4yMDQuMjUwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6InVzYS13YXNoaW5ndG9uLmx2dWZ0LmNvbSIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HqfCfh6og5b635Zu9IDAwMiIsImFkZCI6IjE0Ni4wLjQyLjg3IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJhYmE1MGRkNC01NDg0LTNiMDUtYjE0YS00NjYxY2FmODYyZDUiLCJhaWQiOiI0IiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzIiwiaG9zdCI6Imdlcm1hbnktZHVzc2VsZG9yZi5tYWgzSG9ldC5jb20iLCJ0bHMiOiJ0bHMifQ==
    trojan://02e653c9-7c93-46a9-999d-11834bd0c577@jgwld1.gaox.ml:443?allowInsecure=1#%F0%9F%87%AC%F0%9F%87%A7%20GB%201%20%E2%86%92%20t.me%2Fs%2FSCINV
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDE2NyIsImFkZCI6IjE1MC4yMzAuNDEuOSIsInBvcnQiOiIyMzI5MiIsInR5cGUiOiJub25lIiwiaWQiOiI5NTZjNmMyZi1iZjU0LTRiODctZmFmZC00Yjc2N2NhMTI3NTAiLCJhaWQiOiIwIiwibmV0IjoidGNwIiwicGF0aCI6Ii8iLCJob3N0IjoiMzQuMjE1LjEzMC4xODYiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA1OCIsImFkZCI6Imllc2VpMWVpLmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYWJhNTBkZDQtNTQ4NC0zYjA1LWIxNGEtNDY2MWNhZjg2MmQ1IiwiYWlkIjoiNCIsIm5ldCI6IndzIiwicGF0aCI6Ii93cyIsImhvc3QiOiJpZXNlaTFlaS5jb20iLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoi8J+HuvCfh7gg576O5Zu9IDA0NSIsImFkZCI6IjE3My44Mi4yMjYuMjciLCJwb3J0IjoiMjM2NjIiLCJ0eXBlIjoibm9uZSIsImlkIjoiZWZhMmFiNzYtNTM5ZC00YjZhLTk1NzItMjRiYTcwOWZiODFiIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiMTczLjgyLjIyNi4yNyIsInRscyI6IiJ9

</details>

### 所有节点
合并节点总数: `4878`
[节点链接](https://raw.githubusercontent.com/alanbobs999/TopFreeProxies/master/sub/sub_merge.txt)

### 节点来源
- [pojiezhiyuanjun/freev2](https://github.com/pojiezhiyuanjun/freev2), 节点数量: `77`
- [chfchf0306/clash](https://github.com/chfchf0306/clash), 节点数量: `448`
- [xiyaowong/freeFQ](https://github.com/xiyaowong/freeFQ), 节点数量: `126`
- [freefq/free](https://github.com/freefq/free), 节点数量: `21`
- [learnhard-cn/free_proxy_ss](https://github.com/learnhard-cn/free_proxy_ss), 节点数量: `53`
- [vpei/Free-Node-Merge](https://github.com/vpei/Free-Node-Merge), 节点数量: `100`
- [colatiger/v2ray-nodes](https://github.com/colatiger/v2ray-nodes), 节点数量: `87`
- [oslook/clash-freenode](https://github.com/oslook/clash-freenode), 节点数量: `42`
- [ssrsub/ssr](https://github.com/ssrsub/ssr), 节点数量: `95`
- [Leon406/SubCrawler](https://github.com/Leon406/SubCrawler), 节点数量: `2725`
- [yu-steven/openit](https://github.com/yu-steven/openit), 节点数量: `59`
- [iwxf/free-v2ray](https://github.com/iwxf/free-v2ray), 节点数量: `8`
- [gooooooooooooogle/Clash-Config](https://github.com/gooooooooooooogle/Clash-Config), 节点数量: `1`
- [Jsnzkpg/Jsnzkpg](https://github.com/Jsnzkpg/Jsnzkpg), 节点数量: `17`
- [ermaozi/get_subscribe](https://github.com/ermaozi/get_subscribe), 节点数量: `50`
- [wrfree/free](https://github.com/wrfree/free), 节点数量: `21`
- [GreenFishStudio/GreenFish](https://github.com/GreenFishStudio/GreenFish), 节点数量: `56`
- [changfengoss](https://github.com/ronghuaxueleng/get_v2), 节点数量: `17`
- [anaer/Sub](https://github.com/anaer/Sub), 节点数量: `239`
- [xrayfree/free-ssr-ss-v2ray-vpn-clash](https://github.com/xrayfree/free-ssr-ss-v2ray-vpn-clash), 节点数量: `4`
- [mhmhone/shadowrocket-free-subscribe](https://github.com/mhmhone/shadowrocket-free-subscribe), 节点数量: `16`
- [aiboboxx/v2rayfree](https://github.com/aiboboxx/v2rayfree), 节点数量: `22`
- [moneyfly1/sublist](https://github.com/moneyfly1/sublist), 节点数量: `435`
- [Pawdroid/Free-servers](https://github.com/Pawdroid/Free-servers), 节点数量: `10`
- [kxswa/k](https://github.com/kxswa/k), 节点数量: `0`
- [Nodefree.org](https://github.com/Fukki-Z/nodefree), 节点数量: `50`

## 客户端选择
### 主流桌面客户端
|                            MacOS                             |                            Linux                             |                           Windows                            | 简易描述                                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :------------------------------------------------- |
| [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) | [CFW(Clash For Windows)](https://github.com/Fndroid/clash_for_windows_pkg/releases) | SS, SSR, Trojan, Vmess, VLESS协议支持，策略分流能力强。            |
|     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      |     [Qv2ray](https://github.com/Qv2ray/Qv2ray/releases)      | SS, SSR, Trojan, Vmess, VLESS, Trojan-Go协议支持（需安装相关插件）。 |
|                              ×                               |                              ×                               |      [V2rayN](https://github.com/2dust/v2rayN/releases)      | SS, Trojan, Vmess, VLESS协议支持，有测速，测延迟功能，支持订阅，二维码，剪贴板导入及手动配置。                 |
|                              ×                               |                              ×                               |    [WinXray](https://github.com/TheMRLL/winxray/releases)    | SS, SSR, Trojan, Vmess, VLESS协议支持，支持自动连接最快节点。            |
|                              ×                               |                              ×                               | [Shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows/releases) | SS协议支持， SS 专用客户端。                                       |
|                              ×                               |                              ×                               | [ShadowsocksR-windows](https://github.com/HMBSbige/ShadowsocksR-Windows/releases) | SSR协议支持，SSR 专用客户端。                                      |
|                [Surge](https://nssurge.com/)                 |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，著名网络调试工具，策略分流能力强大，需付费。                        |
|   [ClashX](https://github.com/yichengchen/clashX/releases)   |                              ×                               |                              ×                               | SS, SSR, Trojan, Vmess协议支持，占用资源较少。                   |
|      [V2rayU](https://github.com/yanue/V2rayU/releases)      |                              ×                               |                              ×                               | SS, Trojan, Vmess协议支持，支持订阅，二维码，剪贴板导入，手动配置，二维码分享，与 V2RayN 类似。                        |

### 主流移动客户端
|                          iOS/iPadOS                          |                           Android                            | 简易描述                                                     |
| :----------------------------------------------------------: | :----------------------------------------------------------: | ------------------------------------------------------------ |
| [Shadowrocket](https://apps.apple.com/us/app/shadowrocket/id932747118) | [Shadowrocket](https://play.google.com/store/apps/details?id=com.v2cross.proxy) | SS, SSR, Trojan, Vmess, VLESS协议支持，iOS端需在非国区 App Store 购买，美区售价 $2.99；安卓端非与 iOS 端同一作者，不支持 SSR 协议，免费且内置免费节点。 |
|                [Surge](https://nssurge.com/)                 |                              ×                               | SS, Trojan, Vmess协议支持，iOS 端著名网络调试工具，需付费。                                  |
| [Quantumult X](https://apps.apple.com/us/app/quantumult-x/id1443988620) |                              ×                               | SS, SSR, Trojan, Vmess协议支持，需在非国区AppStore购买，美区售价$4.99。 |
| [Potatso Lite](https://apps.apple.com/us/app/potatso-lite/id1239860606) |                              ×                               | SS, SSR协议支持，需在非国区AppStore购买，免费。              |
|                              ×                               | [Surfboard](https://play.google.com/store/apps/details?id=com.getsurfboard) | SS, SSR, Vmess协议支持，安卓端网络调试软件，兼容 Surge 2 配置。 |
|                              ×                               | [CFA(Clash For Android)](https://github.com/Kr328/ClashForAndroid/releases) | SS, SSR, Trojan, Vmess协议支持。                             |
|                              ×                               |  [SagerNet](https://github.com/SagerNet/SagerNet/releases)   | SS, SSR, Trojan, Vmess, VLESS协议支持。                      |
|                              ×                               | [Shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android/releases) | SS协议支持，安卓专用 SS 客户端。                                                 |
|                              ×                               | [ShadowsocksR-android](https://github.com/HMBSbige/ShadowsocksR-Android/releases) | SSR协议支持，安卓专用 SSR 客户端。                                                |
|                              ×                               |     [V2rayNG](https://github.com/2dust/v2rayNG/releases)     | SS, Trojan, Vmess, VLESS协议支持，v2ray 内核。                           |

## 机场推荐
免费节点失效太快，推荐一些性价比高的机场应急使用。
- [魔戒.net](https://www.mojie.cyou/#/register?code=sAbl0qtT)
  - 按量计费机场, 1¥10G, 10¥130G
  - 所有套餐均是一样的节点与一样的服务，所有套餐流量永不过期，用完为止，不限制客户端数量，最高可提供 2Gbps 峰值
- [大迅云](https://daxun.club/#/register?code=JPmAFPav)
  - 最低月付 5¥50G, 12¥200G, 购买 12¥ 及以上套餐免费领取奈飞 + 迪士尼 Plus 共享号
  - 原生IP负载均衡，流媒体解锁晚高峰油管秒开，主打性价比，有试用
- [阿伟云](https://awslcn.xyz/#/register?code=8C18uZwl)
  - 最低月付 1¥ 起, 9.99¥100G
  - 无带宽速率限制，有流媒体解锁，香港 BGP 中继线路

## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

## 星标统计
[![Star History Chart](https://api.star-history.com/svg?repos=alanbobs999/TopFreeProxies&type=Date)](https://star-history.com/#alanbobs999/TopFreeProxies&Date)