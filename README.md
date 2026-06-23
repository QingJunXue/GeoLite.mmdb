# GeoLite.mmdb

Automated GeoLite2 MMDB mirror updated by GitHub Actions.

## Update schedule

This repository updates automatically every Friday at 20:00 China Standard Time (UTC+8).

GitHub Actions cron uses UTC, so the workflow schedule is:

```yaml
cron: "0 12 * * 5"
```

## Download branch URLs

```text
https://raw.githubusercontent.com/QingJunXue/GeoLite.mmdb/download/GeoLite2-ASN.mmdb
https://raw.githubusercontent.com/QingJunXue/GeoLite.mmdb/download/GeoLite2-City.mmdb
https://raw.githubusercontent.com/QingJunXue/GeoLite.mmdb/download/GeoLite2-Country.mmdb
```

## Releases

Each successful workflow run creates or updates a dated GitHub Release with:

- `GeoLite2-ASN.mmdb`
- `GeoLite2-City.mmdb`
- `GeoLite2-Country.mmdb`
- `SHA256SUMS`

## Manual update

You can also run the workflow manually:

```text
Actions -> Update GeoLite MMDB -> Run workflow
```
