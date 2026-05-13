# 腾讯网 - 最新辟谣

## Coverage
`index-only`

## Route
- Namespace: `qq`
- Namespace Name: `腾讯网`
- Route Path: `/fact`
- Route Name: `最新辟谣`
- Example: `/qq/fact`
- URL: `vp.fact.qq.com/home`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `hoilc`
- Source Location: `fact/index.tsx`
- Source Module: `() => import('@/routes/qq/fact/index.tsx')`

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
  - `vp.fact.qq.com/home`
  - `vp.fact.qq.com/`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/qq/fact",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "fact/index.tsx",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/qq/fact/index.tsx')",
  "name": "最新辟谣",
  "parameters": {},
  "path": "/fact",
  "radar": [
    {
      "source": [
        "vp.fact.qq.com/home",
        "vp.fact.qq.com/"
      ]
    }
  ],
  "url": "vp.fact.qq.com/home"
}
```
