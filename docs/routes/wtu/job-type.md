# 武汉纺织大学 - 就业信息

## Coverage
`index-only`

## Route
- Namespace: `wtu`
- Namespace Name: `武汉纺织大学`
- Route Path: `/job/:type`
- Route Name: `就业信息`
- Example: `/wtu/job/xxtz`
- URL: `wtu.91wllm.com`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ticks-tan`
- Source Location: `job.ts`
- Source Module: `() => import('@/routes/wtu/job.ts')`

## Description
| 信息类型 | 消息通知 | 通知公告 | 新闻快递 |
| -------- | -------- | -------- | -------- |
| 参数     | xxtz     | tzgg     | xwkd     |

## Parameters
- `type`: 信息类型


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
  - `wtu.91wllm.com/news/index/tag/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 信息类型 | 消息通知 | 通知公告 | 新闻快递 |\n| -------- | -------- | -------- | -------- |\n| 参数     | xxtz     | tzgg     | xwkd     |",
  "example": "/wtu/job/xxtz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "job.ts",
  "maintainers": [
    "ticks-tan"
  ],
  "module": "() => import('@/routes/wtu/job.ts')",
  "name": "就业信息",
  "parameters": {
    "type": "信息类型"
  },
  "path": "/job/:type",
  "radar": [
    {
      "source": [
        "wtu.91wllm.com/news/index/tag/:type"
      ]
    }
  ]
}
```
