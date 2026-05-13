# 财联社 - 电报

## Coverage
`index-only`

## Route
- Namespace: `cls`
- Namespace Name: `财联社`
- Route Path: `/telegraph/:category?`
- Route Name: `电报`
- Example: `/cls/telegraph`
- URL: `cls.cn/telegraph`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `telegraph.tsx`
- Source Module: `() => import('@/routes/cls/telegraph.tsx')`

## Description
| 看盘  | 公司         | 解读    | 加红 | 推送  | 提醒   | 基金 | 港股 |
| ----- | ------------ | ------- | ---- | ----- | ------ | ---- | ---- |
| watch | announcement | explain | red  | jpush | remind | fund | hk   |

## Parameters
- `category`: 分类，见下表，默认为全部


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
  - `cls.cn/telegraph`
  - `cls.cn/`
- `target`: `/telegraph`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 看盘  | 公司         | 解读    | 加红 | 推送  | 提醒   | 基金 | 港股 |\n| ----- | ------------ | ------- | ---- | ----- | ------ | ---- | ---- |\n| watch | announcement | explain | red  | jpush | remind | fund | hk   |",
  "example": "/cls/telegraph",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "telegraph.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cls/telegraph.tsx')",
  "name": "电报",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/telegraph/:category?",
  "radar": [
    {
      "source": [
        "cls.cn/telegraph",
        "cls.cn/"
      ],
      "target": "/telegraph"
    }
  ],
  "url": "cls.cn/telegraph"
}
```
