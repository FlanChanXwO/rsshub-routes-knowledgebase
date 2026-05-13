# FINAL FANTASY XIV - 最终幻想 14 国服

## Coverage
`index-only`

## Route
- Namespace: `ff14`
- Namespace Name: `FINAL FANTASY XIV`
- Route Path: `/zh/:type?`
- Route Name: `最终幻想 14 国服`
- Example: `/ff14/zh/news`
- URL: `ff.web.sdo.com/web8/index.html`
- Language: `en`
- Categories: `game`
- Maintainers: `Kiotlin, ZeroClad, 15x15G`
- Source Location: `ff14-zh.ts`
- Source Module: `() => import('@/routes/ff14/ff14-zh.ts')`

## Description
| 新闻 | 公告     | 活动   | 广告      | 所有 |
| ---- | -------- | ------ | --------- | ---- |
| news | announce | events | advertise | all  |

## Parameters
- `type`: 分类名，预设为 `all`


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
  - `ff.web.sdo.com/web8/index.html`
- `target`: `/zh`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 新闻 | 公告     | 活动   | 广告      | 所有 |\n| ---- | -------- | ------ | --------- | ---- |\n| news | announce | events | advertise | all  |",
  "example": "/ff14/zh/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ff14-zh.ts",
  "maintainers": [
    "Kiotlin",
    "ZeroClad",
    "15x15G"
  ],
  "module": "() => import('@/routes/ff14/ff14-zh.ts')",
  "name": "最终幻想 14 国服",
  "parameters": {
    "type": "分类名，预设为 `all`"
  },
  "path": [
    "/zh/:type?",
    "/ff14_zh/:type?"
  ],
  "radar": [
    {
      "source": [
        "ff.web.sdo.com/web8/index.html"
      ],
      "target": "/zh"
    }
  ],
  "url": "ff.web.sdo.com/web8/index.html"
}
```
