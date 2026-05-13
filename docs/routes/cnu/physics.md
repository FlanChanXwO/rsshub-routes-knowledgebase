# 首都师范大学 - 物理系院系新闻

## Coverage
`index-only`

## Route
- Namespace: `cnu`
- Namespace Name: `首都师范大学`
- Route Path: `/physics`
- Route Name: `物理系院系新闻`
- Example: `/cnu/physics`
- URL: `physics.cnu.edu.cn/news/index.htm`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `liueic`
- Source Location: `physics.ts`
- Source Module: `() => import('@/routes/cnu/physics.ts')`

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
  - `physics.cnu.edu.cn/news/index.htm`
- `target`: `/cnu/physics`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cnu/physics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "physics.ts",
  "maintainers": [
    "liueic"
  ],
  "module": "() => import('@/routes/cnu/physics.ts')",
  "name": "物理系院系新闻",
  "parameters": {},
  "path": "/physics",
  "radar": [
    {
      "source": [
        "physics.cnu.edu.cn/news/index.htm"
      ],
      "target": "/cnu/physics"
    }
  ],
  "url": "physics.cnu.edu.cn/news/index.htm"
}
```
