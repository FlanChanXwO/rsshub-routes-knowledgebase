# 厦门网 - 数字媒体

## Coverage
`index-only`

## Route
- Namespace: `xmnn`
- Namespace Name: `厦门网`
- Route Path: `/epaper/:id?`
- Route Name: `数字媒体`
- Example: `/xmnn/epaper/xmrb`
- URL: `epaper.xmnn.cn`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `epaper.ts`
- Source Module: `() => import('@/routes/xmnn/epaper.ts')`

## Description
| 厦门日报 | 厦门晚报 | 海西晨报 | 城市捷报 |
| -------- | -------- | -------- | -------- |
| xmrb     | xmwb     | hxcb     | csjb     |

## Parameters
- `id`: 报纸 id，见下表，默认为 `xmrb`，即厦门日报


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
  - `epaper.xmnn.cn/:id`
- `target`: `/epaper/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 厦门日报 | 厦门晚报 | 海西晨报 | 城市捷报 |\n| -------- | -------- | -------- | -------- |\n| xmrb     | xmwb     | hxcb     | csjb     |",
  "example": "/xmnn/epaper/xmrb",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "epaper.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/xmnn/epaper.ts')",
  "name": "数字媒体",
  "parameters": {
    "id": "报纸 id，见下表，默认为 `xmrb`，即厦门日报"
  },
  "path": "/epaper/:id?",
  "radar": [
    {
      "source": [
        "epaper.xmnn.cn/:id"
      ],
      "target": "/epaper/:id"
    }
  ]
}
```
