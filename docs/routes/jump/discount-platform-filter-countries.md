# JUMP - 游戏折扣

## Coverage
`index-only`

## Route
- Namespace: `jump`
- Namespace Name: `JUMP`
- Route Path: `/discount/:platform/:filter?/:countries?`
- Route Name: `游戏折扣`
- Example: `/jump/discount/ps5/all`
- URL: `switch.jumpvg.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `zytomorrow`
- Source Location: `discount.tsx`
- Source Module: `() => import('@/routes/jump/discount.tsx')`

## Description
| switch | ps4  | ps5  | xbox   | steam | epic   |
| ------ | ---- | ---- | ------ | ----- | ------ |
| 可用   | 可用 | 可用 | 不可用 | 可用  | 不可用 |

| filter | switch | ps4 | ps5 | steam |
| ------ | ------ | --- | --- | ----- |
| all    | ✔     | ✔  | ✔  | ✔    |
| jx     | ✔     | ✔  | ❌  | ✔    |
| sd     | ✔     | ✔  | ✔  | ✔    |
| dl     | ❌     | ✔  | ❌  | ✔    |
| vip    | ❌     | ❌  | ✔  | ❌    |

| 北美 | 欧洲（英语） | 法国 | 德国 | 日本 |
| ---- | ------------ | ---- | ---- | ---- |
| na   | eu           | fr   | de   | jp   |

## Parameters
- `platform`: 平台:switch,ps4,ps5,xbox,steam,epic
- `filter`: 过滤参数,all-全部，jx-精选，sd-史低，dl-独立，vip-会员
- `countries`: 地区，具体支持较多，可自信查看地区简写


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
  "description": "| switch | ps4  | ps5  | xbox   | steam | epic   |\n| ------ | ---- | ---- | ------ | ----- | ------ |\n| 可用   | 可用 | 可用 | 不可用 | 可用  | 不可用 |\n\n| filter | switch | ps4 | ps5 | steam |\n| ------ | ------ | --- | --- | ----- |\n| all    | ✔     | ✔  | ✔  | ✔    |\n| jx     | ✔     | ✔  | ❌  | ✔    |\n| sd     | ✔     | ✔  | ✔  | ✔    |\n| dl     | ❌     | ✔  | ❌  | ✔    |\n| vip    | ❌     | ❌  | ✔  | ❌    |\n\n| 北美 | 欧洲（英语） | 法国 | 德国 | 日本 |\n| ---- | ------------ | ---- | ---- | ---- |\n| na   | eu           | fr   | de   | jp   |",
  "example": "/jump/discount/ps5/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "discount.tsx",
  "maintainers": [
    "zytomorrow"
  ],
  "module": "() => import('@/routes/jump/discount.tsx')",
  "name": "游戏折扣",
  "parameters": {
    "countries": "地区，具体支持较多，可自信查看地区简写",
    "filter": "过滤参数,all-全部，jx-精选，sd-史低，dl-独立，vip-会员",
    "platform": "平台:switch,ps4,ps5,xbox,steam,epic"
  },
  "path": "/discount/:platform/:filter?/:countries?"
}
```
