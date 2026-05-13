# 网易公开课 - 人间

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/renjian/:category?`
- Route Name: `人间`
- Example: `/163/renjian/texie`
- URL: `163.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `renjian.ts`
- Source Module: `() => import('@/routes/163/renjian.ts')`

## Description
| 特写  | 记事  | 大写  | 好读  | 看客  |
| ----- | ----- | ----- | ----- | ----- |
| texie | jishi | daxie | haodu | kanke |

## Parameters
- `category`: 分类，见下表，默认为特写


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
  - `renjian.163.com/:category`
  - `renjian.163.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 特写  | 记事  | 大写  | 好读  | 看客  |\n| ----- | ----- | ----- | ----- | ----- |\n| texie | jishi | daxie | haodu | kanke |",
  "example": "/163/renjian/texie",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "renjian.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/163/renjian.ts')",
  "name": "人间",
  "parameters": {
    "category": "分类，见下表，默认为特写"
  },
  "path": "/renjian/:category?",
  "radar": [
    {
      "source": [
        "renjian.163.com/:category",
        "renjian.163.com/"
      ]
    }
  ]
}
```
