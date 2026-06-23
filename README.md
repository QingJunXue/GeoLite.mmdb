# GeoLite.mmdb

MaxMind GeoLite2 Country、City 和 ASN 数据库镜像。

本仓库通过 GitHub Actions 自动更新，更新时间为每周五 20:00（中国标准时间，UTC+8）。

## 下载

### Raw 直链

- [GeoLite2-ASN.mmdb](https://raw.githubusercontent.com/QingJunXue/GeoLite.mmdb/download/GeoLite2-ASN.mmdb)
- [GeoLite2-City.mmdb](https://raw.githubusercontent.com/QingJunXue/GeoLite.mmdb/download/GeoLite2-City.mmdb)
- [GeoLite2-Country.mmdb](https://raw.githubusercontent.com/QingJunXue/GeoLite.mmdb/download/GeoLite2-Country.mmdb)
- [SHA256SUMS](https://raw.githubusercontent.com/QingJunXue/GeoLite.mmdb/download/SHA256SUMS)

### Releases

也可以从最新 Release 下载：

https://github.com/QingJunXue/GeoLite.mmdb/releases/latest

## 更新时间

每周五 20:00（中国标准时间，UTC+8）自动更新。

GitHub Actions 的 cron 使用 UTC 时间，因此配置为：

```yaml
cron: "0 12 * * 5"
```

## 手动更新

如需立即更新，可以手动运行 workflow：

```text
Actions -> Update GeoLite MMDB -> Run workflow
```

## 文件说明

- `GeoLite2-ASN.mmdb`
- `GeoLite2-City.mmdb`
- `GeoLite2-Country.mmdb`
- `SHA256SUMS`

## 授权

数据库及内容版权归 MaxMind, Inc. 所有。

GeoLite2 数据受 GeoLite2 End User License Agreement 约束。
