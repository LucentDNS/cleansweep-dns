# CleanSweep DNS

> One list to sweep them all — ads, in-app ads, trackers, telemetry,
> phishing, scams and malware.

[![Build](https://github.com/LucentDNS/cleansweep-dns/actions/workflows/build.yml/badge.svg)](https://github.com/LucentDNS/cleansweep-dns/actions/workflows/build.yml)

A curated, all-in-one DNS blocklist for **AdGuard Home** and **AdGuard for Android**. Compiled daily via GitHub Actions from world-class upstream sources.

## 订阅链接 (Subscribe)

| Channel | URL |
|---|---|
| GitHub Raw (推荐) | `https://raw.githubusercontent.com/LucentDNS/cleansweep-dns/main/filter.txt` |
| jsDelivr CDN (国内可达, 约 12h 缓存) | `https://cdn.jsdelivr.net/gh/LucentDNS/cleansweep-dns@main/filter.txt` |

## What it blocks
- Web & in-app ads, trackers, telemetry, crypto miners
- Phishing, scams, malware & C2 domains
- Affiliate / referral junk

## Sources
- [HaGeZi's Pro Blocklist](https://github.com/hagezi/dns-blocklists) + Threat Intelligence Feeds (Mini)
- [AdGuard Chinese filter](https://github.com/AdguardTeam/AdguardFilters) & [EasyList China](https://github.com/easylist/easylistchina)
- Custom curated rules

Full credits and licenses belong to the upstream authors. This list only aggregates and normalizes them for DNS-level blocking.

## Usage
- **AdGuard Home**: Filters → DNS blocklists → Add blocklist → paste URL
- **AdGuard Android**: Settings → DNS protection → DNS blocklists → Add → paste URL

## License
GPL-3.0
