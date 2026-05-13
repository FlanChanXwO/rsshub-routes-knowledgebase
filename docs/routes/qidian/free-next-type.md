# 起点 - 限时免费下期预告

## Coverage
`index-only`

## Route
- Namespace: `qidian`
- Namespace Name: `起点`
- Route Path: `/free-next/:type?`
- Route Name: `限时免费下期预告`
- Example: `/qidian/free-next`
- URL: `www.qidian.com/free`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `LogicJake, pseudoyu`
- Source Location: `free-next.ts`
- Source Module: `() => import('@/routes/qidian/free-next.ts')`

## Description
_None_

## Parameters
- `type`: 默认不填为起点中文网，填 mm 为起点女生网


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.qidian.com/free`
- `target`: `/free`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/qidian/free-next",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "free-next.ts",
  "maintainers": [
    "LogicJake",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/qidian/free-next.ts')",
  "name": "限时免费下期预告",
  "parameters": {
    "type": "默认不填为起点中文网，填 mm 为起点女生网"
  },
  "path": "/free-next/:type?",
  "radar": [
    {
      "source": [
        "www.qidian.com/free"
      ],
      "target": "/free"
    }
  ],
  "url": "www.qidian.com/free"
}
```
