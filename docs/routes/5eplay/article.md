# 5EPLAY - 新闻列表

## Coverage
`index-only`

## Route
- Namespace: `5eplay`
- Namespace Name: `5EPLAY`
- Route Path: `/article`
- Route Name: `新闻列表`
- Example: `/5eplay/article`
- URL: `csgo.5eplay.com/`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `Dlouxgit`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/5eplay/index.ts')`

## Description
_None_

## Parameters
_None_


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
  - `csgo.5eplay.com/`
  - `csgo.5eplay.com/article`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/5eplay/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "Dlouxgit"
  ],
  "module": "() => import('@/routes/5eplay/index.ts')",
  "name": "新闻列表",
  "parameters": {},
  "path": "/article",
  "radar": [
    {
      "source": [
        "csgo.5eplay.com/",
        "csgo.5eplay.com/article"
      ]
    }
  ],
  "url": "csgo.5eplay.com/"
}
```
