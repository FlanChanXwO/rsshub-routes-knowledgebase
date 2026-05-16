# JUMP - 游戏折扣

## Coverage
`index-only`

## Route
- Namespace: `jump`
- Namespace Name: `JUMP`
- Route Path: `/jump/discount/:platform/:filter?/:countries?`
- Route Name: `游戏折扣`
- Example: `/jump/discount/ps5/all`
- URL: `switch.jumpvg.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `zytomorrow`
- Source Location: `discount.tsx`
- Source Module: `_None_`

## Description
| switch | ps4  | ps5  | xbox   | steam | epic   |
| ------ | ---- | ---- | ------ | ----- | ------ |
| 可用   | 可用 | 可用 | 不可用 | 可用  | 不可用 |

| filter | switch | ps4 | ps5 | steam |
| ------ | ------ | --- | --- | ----- |
| all    | ✔      | ✔   | ✔   | ✔     |
| jx     | ✔      | ✔   | ❌  | ✔     |
| sd     | ✔      | ✔   | ✔   | ✔     |
| dl     | ❌     | ✔   | ❌  | ✔     |
| vip    | ❌     | ❌  | ✔   | ❌    |

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
  "description": "| switch | ps4  | ps5  | xbox   | steam | epic   |\n| ------ | ---- | ---- | ------ | ----- | ------ |\n| 可用   | 可用 | 可用 | 不可用 | 可用  | 不可用 |\n\n| filter | switch | ps4 | ps5 | steam |\n| ------ | ------ | --- | --- | ----- |\n| all    | ✔      | ✔   | ✔   | ✔     |\n| jx     | ✔      | ✔   | ❌  | ✔     |\n| sd     | ✔      | ✔   | ✔   | ✔     |\n| dl     | ❌     | ✔   | ❌  | ✔     |\n| vip    | ❌     | ❌  | ✔   | ❌    |\n\n| 北美 | 欧洲（英语） | 法国 | 德国 | 日本 |\n| ---- | ------------ | ---- | ---- | ---- |\n| na   | eu           | fr   | de   | jp   |",
  "example": "/jump/discount/ps5/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 73,
  "location": "discount.tsx",
  "maintainers": [
    "zytomorrow"
  ],
  "name": "游戏折扣",
  "parameters": {
    "countries": "地区，具体支持较多，可自信查看地区简写",
    "filter": "过滤参数,all-全部，jx-精选，sd-史低，dl-独立，vip-会员",
    "platform": "平台:switch,ps4,ps5,xbox,steam,epic"
  },
  "path": "/discount/:platform/:filter?/:countries?",
  "topFeeds": [
    {
      "description": "jump 发现游戏 - Powered by RSSHub",
      "errorAt": "2026-05-12T18:02:13.759Z",
      "errorMessage": "Failed to fetch\n",
      "id": "66698425520730122",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jumpvg.com/",
      "title": "jump 折扣-ps5-全部",
      "type": "feed",
      "url": "rsshub://jump/discount/ps5/all"
    },
    {
      "description": "jump 发现游戏 - Powered by RSSHub",
      "errorAt": "2026-05-05T22:28:03.155Z",
      "errorMessage": "Failed to fetch\n",
      "id": "79731667838042112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jumpvg.com/",
      "title": "jump 折扣-switch-全部",
      "type": "feed",
      "url": "rsshub://jump/discount/switch/all"
    }
  ]
}
```
