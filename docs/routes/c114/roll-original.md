# C114 通信网 - 滚动资讯

## Coverage
`index-only`

## Route
- Namespace: `c114`
- Namespace Name: `C114 通信网`
- Route Path: `/roll/:original?`
- Route Name: `滚动资讯`
- Example: `/c114/roll`
- URL: `c114.com.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `roll.ts`
- Source Module: `() => import('@/routes/c114/roll.ts')`

## Description
_None_

## Parameters
- `original`: 只看原创，可选 true 和 false，默认为 false


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `c114.com.cn/news/roll.asp`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "",
  "example": "/c114/roll",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "roll.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/c114/roll.ts')",
  "name": "滚动资讯",
  "parameters": {
    "original": "只看原创，可选 true 和 false，默认为 false"
  },
  "path": "/roll/:original?",
  "radar": [
    {
      "source": [
        "c114.com.cn/news/roll.asp"
      ]
    }
  ],
  "url": "c114.com.cn"
}
```
