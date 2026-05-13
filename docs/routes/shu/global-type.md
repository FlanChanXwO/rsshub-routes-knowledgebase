# 上海大学 - 国际部港澳台办公室

## Coverage
`index-only`

## Route
- Namespace: `shu`
- Namespace Name: `上海大学`
- Route Path: `/global/:type?`
- Route Name: `国际部港澳台办公室`
- Example: `/shu/global/tzgg`
- URL: `global.shu.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `GhhG123`
- Source Location: `global.ts`
- Source Module: `() => import('@/routes/shu/global.ts')`

## Description
| 通知公告 | 新闻速递 |
| -------- | -------- |
| tzgg     | xwsd     |

## Parameters
- `type`: 分类，默认为通知公告


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
  - `global.shu.edu.cn/cd/tzgg.htm`
  - `global.shu.edu.cn/cd/xwsd.htm`
- `target`: `/global`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 新闻速递 |\n| -------- | -------- |\n| tzgg     | xwsd     |",
  "example": "/shu/global/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "global.ts",
  "maintainers": [
    "GhhG123"
  ],
  "module": "() => import('@/routes/shu/global.ts')",
  "name": "国际部港澳台办公室",
  "parameters": {
    "type": "分类，默认为通知公告"
  },
  "path": "/global/:type?",
  "radar": [
    {
      "source": [
        "global.shu.edu.cn/cd/tzgg.htm",
        "global.shu.edu.cn/cd/xwsd.htm"
      ],
      "target": "/global"
    }
  ],
  "url": "global.shu.edu.cn/"
}
```
