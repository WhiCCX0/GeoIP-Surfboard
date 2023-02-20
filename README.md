Surfboard 可用精简版 GeoIP (cn, privite, google)

同https://github.com/Loyalsoldier/geoip 

由于surfboard使用Country-only-cn-private.mmdb（精简版 GeoIP）时，必须包含8.8.8.8，所以在其基础上加上了geoip:google。

## 使用方法

打开Surfboard - 设置 - VPN - GeoIP数据库 - 填入以下任意一个链接 - 点击更新并保存

  - [https://raw.githubusercontent.com/WhiCCX0/GeoIP-Surfboard/release/Country-only-cn-private-surfboard.mmdb](https://raw.githubusercontent.com/Loyalsoldier/geoip/release/Country-only-cn-private.mmdb)
  - [https://cdn.jsdelivr.net/gh/WhiCCX0/GeoIP-Surfboard@release/Country-only-cn-private-surfboard.mmdb](https://cdn.jsdelivr.net/gh/Loyalsoldier/geoip@release/Country-only-cn-private.mmdb](https://cdn.jsdelivr.net/gh/WhiCCX0/GeoIP-Surfboard@release/Country-only-cn-private-surfboard.mmdb)

> 如果无法访问域名 `raw.githubusercontent.com`，可以使用第二个地址 `cdn.jsdelivr.net`。


# 简介

本项目每周四自动生成 GeoIP MaxMind mmdb 格式文件 `Country.mmdb`。

## 与官方版 GeoIP 的区别

- 中国大陆 IPv4 地址数据融合了 [IPIP.net](https://github.com/17mon/china_ip_list/blob/master/china_ip_list.txt) 和 [@gaoyifan/china-operator-ip](https://github.com/gaoyifan/china-operator-ip/blob/ip-lists/china.txt)
- 中国大陆 IPv6 地址数据融合了 MaxMind GeoLite2 和 [@gaoyifan/china-operator-ip](https://github.com/gaoyifan/china-operator-ip/blob/ip-lists/china6.txt)
- 新增类别：
  - `geoip:google`（`GEOIP,GOOGLE`）


## License

[CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)

This product includes GeoLite2 data created by MaxMind, available from [MaxMind](http://www.maxmind.com).
