# PRINCESS CONNECT! Re Dive プリンセスコネクト！Re Dive - 最新公告

## Coverage
`index-only`

## Route
- Namespace: `priconne-redive`
- Namespace Name: `PRINCESS CONNECT! Re Dive プリンセスコネクト！Re Dive`
- Route Path: `/news/:server?`
- Route Name: `最新公告`
- Example: `/priconne-redive/news`
- URL: `priconne-redive.jp/news`
- Language: `ja`
- Categories: `game`
- Maintainers: `SayaSS, frankcwl`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/priconne-redive/news.ts')`

## Description
服务器

| 国服  | 台服  | 日服  |
| ----- | ----- | ---- |
| zh-cn | zh-tw | jp   |

## Parameters
- `server`: 服务器，默认日服


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `priconne-redive.jp/news`
- `target`: `/news/jp`
### Rule 2
- `source`:
  - `princessconnect.so-net.tw/news`
- `target`: `/news/zh-tw`
### Rule 3
- `source`:
  - `game.bilibili.com/pcr/news.html`
- `target`: `/news/zh-cn`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "服务器\n\n| 国服  | 台服  | 日服  |\n| ----- | ----- | ---- |\n| zh-cn | zh-tw | jp   |",
  "example": "/priconne-redive/news",
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
    "SayaSS",
    "frankcwl"
  ],
  "module": "() => import('@/routes/priconne-redive/news.ts')",
  "name": "最新公告",
  "parameters": {
    "server": "服务器，默认日服"
  },
  "path": "/news/:server?",
  "radar": [
    {
      "source": [
        "priconne-redive.jp/news"
      ],
      "target": "/news/jp"
    },
    {
      "source": [
        "princessconnect.so-net.tw/news"
      ],
      "target": "/news/zh-tw"
    },
    {
      "source": [
        "game.bilibili.com/pcr/news.html"
      ],
      "target": "/news/zh-cn"
    }
  ],
  "url": "priconne-redive.jp/news"
}
```
