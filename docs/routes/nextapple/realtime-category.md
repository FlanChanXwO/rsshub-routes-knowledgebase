# 壹蘋新聞網 - 最新新聞

## Coverage
`index-only`

## Route
- Namespace: `nextapple`
- Namespace Name: `壹蘋新聞網`
- Route Path: `/realtime/:category?`
- Route Name: `最新新聞`
- Example: `/nextapple/realtime/latest`
- URL: `tw.nextapple.com/`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `miles170`
- Source Location: `realtime.ts`
- Source Module: `() => import('@/routes/nextapple/realtime.ts')`

## Description
| 首頁   | 焦點      | 熱門 | 娛樂          | 生活 | 女神     | 社會  |
| ------ | --------- | ---- | ------------- | ---- | -------- | ----- |
| latest | recommend | hit  | entertainment | life | gorgeous | local |

| 政治     | 國際          | 財經    | 體育   | 旅遊美食  | 3C 車市 |
| -------- | ------------- | ------- | ------ | --------- | ------- |
| politics | international | finance | sports | lifestyle | gadget  |

## Parameters
- `category`: 類別，見下表，默認為首頁


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
  - `tw.nextapple.com/`
  - `tw.nextapple.com/realtime/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 首頁   | 焦點      | 熱門 | 娛樂          | 生活 | 女神     | 社會  |\n| ------ | --------- | ---- | ------------- | ---- | -------- | ----- |\n| latest | recommend | hit  | entertainment | life | gorgeous | local |\n\n| 政治     | 國際          | 財經    | 體育   | 旅遊美食  | 3C 車市 |\n| -------- | ------------- | ------- | ------ | --------- | ------- |\n| politics | international | finance | sports | lifestyle | gadget  |",
  "example": "/nextapple/realtime/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "realtime.ts",
  "maintainers": [
    "miles170"
  ],
  "module": "() => import('@/routes/nextapple/realtime.ts')",
  "name": "最新新聞",
  "parameters": {
    "category": "類別，見下表，默認為首頁"
  },
  "path": "/realtime/:category?",
  "radar": [
    {
      "source": [
        "tw.nextapple.com/",
        "tw.nextapple.com/realtime/:category"
      ]
    }
  ],
  "url": "tw.nextapple.com/"
}
```
