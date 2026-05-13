# 煎蛋 - Feed

## Coverage
`index-only`

## Route
- Namespace: `jandan`
- Namespace Name: `煎蛋`
- Route Path: `/`
- Route Name: `Feed`
- Example: `/jandan`
- URL: `jandan.net`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `nczitzk, bigfei, pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/jandan/index.ts')`

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
  - `i.jandan.net`
- `target`: `/jandan`

## Raw JSON
```json
{
  "example": "/jandan",
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
    "nczitzk",
    "bigfei",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/jandan/index.ts')",
  "name": "Feed",
  "parameters": {},
  "path": "/",
  "radar": [
    {
      "source": [
        "i.jandan.net"
      ],
      "target": "/jandan"
    }
  ]
}
```
