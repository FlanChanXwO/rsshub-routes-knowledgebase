# 中国人事考试网 - 中国人事考试网发布

## Coverage
`index-only`

## Route
- Namespace: `cpta`
- Namespace Name: `中国人事考试网`
- Route Path: `/:category`
- Route Name: `中国人事考试网发布`
- Example: `/cpta/notice`
- URL: `www.cpta.com.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `PrinOrange`
- Source Location: `handler.ts`
- Source Module: `() => import('@/routes/cpta/handler.ts')`

## Description
| Category    | Title     | Description                         |
|-------------|-----------|-------------------------------------|
| notice      | 通知公告  | 中国人事考试网 考试通知公告汇总    |
| performance | 成绩公布  | 中国人事考试网 考试成绩公布汇总    |

## Parameters
- `category`: 栏目参数，可见下表描述。


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true
- `antiCrawler`: true

## Radar
### Rule 1
- `title`: `中国人事考试网通知公告`
- `source`:
  - `www.cpta.com.cn/notice.html`
  - `www.cpta.com.cn`
- `target`: `/notice`
### Rule 2
- `title`: `中国人事考试网成绩发布`
- `source`:
  - `www.cpta.com.cn/performance.html`
  - `www.cpta.com.cn`
- `target`: `/performance`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "\n| Category    | Title     | Description                         |\n|-------------|-----------|-------------------------------------|\n| notice      | 通知公告  | 中国人事考试网 考试通知公告汇总    |\n| performance | 成绩公布  | 中国人事考试网 考试成绩公布汇总    |\n",
  "example": "/cpta/notice",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "handler.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "module": "() => import('@/routes/cpta/handler.ts')",
  "name": "中国人事考试网发布",
  "parameters": {
    "category": "栏目参数，可见下表描述。"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "www.cpta.com.cn/notice.html",
        "www.cpta.com.cn"
      ],
      "target": "/notice",
      "title": "中国人事考试网通知公告"
    },
    {
      "source": [
        "www.cpta.com.cn/performance.html",
        "www.cpta.com.cn"
      ],
      "target": "/performance",
      "title": "中国人事考试网成绩发布"
    }
  ]
}
```
