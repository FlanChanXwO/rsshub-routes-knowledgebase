# 停水通知 - 南京市

## Coverage
`index-only`

## Route
- Namespace: `tingshuitz`
- Namespace Name: `停水通知`
- Route Path: `/nanjing`
- Route Name: `南京市`
- Example: `/tingshuitz/nanjing`
- URL: `jlwater.com/portal/10000015`
- Language: `zh-CN`
- Categories: `forecast`
- Maintainers: `ocleo1, pseudoyu`
- Source Location: `nanjing.ts`
- Source Module: `() => import('@/routes/tingshuitz/nanjing.ts')`

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
  - `jlwater.com/portal/10000015`
  - `jlwater.com/`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/tingshuitz/nanjing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "nanjing.ts",
  "maintainers": [
    "ocleo1",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/tingshuitz/nanjing.ts')",
  "name": "南京市",
  "parameters": {},
  "path": "/nanjing",
  "radar": [
    {
      "source": [
        "jlwater.com/portal/10000015",
        "jlwater.com/"
      ]
    }
  ],
  "url": "jlwater.com/portal/10000015"
}
```
