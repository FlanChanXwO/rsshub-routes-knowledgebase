# 全国通信专业技术人员职业水平考试 - 通信考试动态

## Coverage
`index-only`

## Route
- Namespace: `txks`
- Namespace Name: `全国通信专业技术人员职业水平考试`
- Route Path: `/news`
- Route Name: `通信考试动态`
- Example: `/txks/news`
- URL: `www.txks.org.cn`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `PrinOrange`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/txks/news.ts')`

## Description
**注意：** 官方网站限制了国外网络请求，可能需要通过部署在中国大陆内的 RSSHub 实例访问。

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `title`: `全国通信专业技术人员职业水平考试动态`
- `source`:
  - `www.txks.org.cn/index/work`
  - `www.txks.org.cn`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "**注意：** 官方网站限制了国外网络请求，可能需要通过部署在中国大陆内的 RSSHub 实例访问。",
  "example": "/txks/news",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "module": "() => import('@/routes/txks/news.ts')",
  "name": "通信考试动态",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.txks.org.cn/index/work",
        "www.txks.org.cn"
      ],
      "target": "/news",
      "title": "全国通信专业技术人员职业水平考试动态"
    }
  ]
}
```
