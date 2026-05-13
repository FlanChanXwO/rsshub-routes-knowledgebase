# Blue Archive - News

## Coverage
`index-only`

## Route
- Namespace: `bluearchive`
- Namespace Name: `Blue Archive`
- Route Path: `/news/:server/:type?`
- Route Name: `News`
- Example: `/bluearchive/news/jp`
- URL: `bluearchive.jp`
- Language: `ja`
- Categories: `game`
- Maintainers: `equt`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/bluearchive/news.ts')`

## Description
| 全て | イベント | お知らせ | メンテナンス |
| :--: | :--: | :--: | :--: |
| 0 | 1 | 2 | 3 |

## Parameters
- `server`: game server (ISO 3166 two-letter country code, case-insensitive), only `JP` is supported for now
- `type`: news type, checkout the table below for details


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
  "description": "| 全て | イベント | お知らせ | メンテナンス |\n| :--: | :--: | :--: | :--: |\n| 0 | 1 | 2 | 3 |",
  "example": "/bluearchive/news/jp",
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
    "equt"
  ],
  "module": "() => import('@/routes/bluearchive/news.ts')",
  "name": "News",
  "parameters": {
    "server": "game server (ISO 3166 two-letter country code, case-insensitive), only `JP` is supported for now",
    "type": "news type, checkout the table below for details"
  },
  "path": "/news/:server/:type?"
}
```
