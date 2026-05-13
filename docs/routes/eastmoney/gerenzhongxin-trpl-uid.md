# 东方财富 - 个人中心评论

## Coverage
`index-only`

## Route
- Namespace: `eastmoney`
- Namespace Name: `东方财富`
- Route Path: `/gerenzhongxin/trpl/:uid`
- Route Name: `个人中心评论`
- Example: `/eastmoney/gerenzhongxin/trpl/2922094262312522`
- URL: `data.eastmoney.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `AwesomeDog`
- Source Location: `gerenzhongxin/trpl.ts`
- Source Module: `() => import('@/routes/eastmoney/gerenzhongxin/trpl.ts')`

## Description
_None_

## Parameters
- `uid`: 用户id,即用户主页网址末尾的数字


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
  - `guba.eastmoney.com`
### Rule 2
- `source`:
  - `caifuhao.eastmoney.com`
### Rule 3
- `source`:
  - `i.eastmoney.com/:uid`
- `target`: `/gerenzhongxin/trpl/:uid`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/eastmoney/gerenzhongxin/trpl/2922094262312522",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gerenzhongxin/trpl.ts",
  "maintainers": [
    "AwesomeDog"
  ],
  "module": "() => import('@/routes/eastmoney/gerenzhongxin/trpl.ts')",
  "name": "个人中心评论",
  "parameters": {
    "uid": "用户id,即用户主页网址末尾的数字"
  },
  "path": "/gerenzhongxin/trpl/:uid",
  "radar": [
    {
      "source": [
        "guba.eastmoney.com"
      ]
    },
    {
      "source": [
        "caifuhao.eastmoney.com"
      ]
    },
    {
      "source": [
        "i.eastmoney.com/:uid"
      ],
      "target": "/gerenzhongxin/trpl/:uid"
    }
  ],
  "view": 0
}
```
