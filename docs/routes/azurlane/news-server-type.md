# Azur Lane - News

## Coverage
`index-only`

## Route
- Namespace: `azurlane`
- Namespace Name: `Azur Lane`
- Route Path: `/news/:server/:type?`
- Route Name: `News`
- Example: `/azurlane/news/jp/0`
- URL: `azurlane.jp`
- Language: `ja`
- Categories: `game`
- Maintainers: `AnitsuriW`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/azurlane/news.ts')`

## Description
| すべて | お知らせ | イベント | メインテナンス | 重要 |
| :--: | :--: | :--: | :--: | :--: |
| 0 | 1 | 2 | 3 | 4 |

## Parameters
- `server`: game server (ISO 3166 two-letter country code, case-insensitive), only `JP` is supported for now
- `type`: news type, see the table below, `0` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| すべて | お知らせ | イベント | メインテナンス | 重要 |\n| :--: | :--: | :--: | :--: | :--: |\n| 0 | 1 | 2 | 3 | 4 |",
  "example": "/azurlane/news/jp/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "AnitsuriW"
  ],
  "module": "() => import('@/routes/azurlane/news.ts')",
  "name": "News",
  "parameters": {
    "server": "game server (ISO 3166 two-letter country code, case-insensitive), only `JP` is supported for now",
    "type": "news type, see the table below, `0` by default"
  },
  "path": "/news/:server/:type?"
}
```
