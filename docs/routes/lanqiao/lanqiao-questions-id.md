# 蓝桥云课 - 技术社区

## Coverage
`index-only`

## Route
- Namespace: `lanqiao`
- Namespace Name: `蓝桥云课`
- Route Path: `/lanqiao/questions/:id`
- Route Name: `技术社区`
- Example: `/lanqiao/questions/2`
- URL: `lanqiao.cn/questions/`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `huhuhang`
- Source Location: `questions.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: topic_id 主题 `id` 可在社区板块 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `lanqiao.cn/questions/`
  - `lanqiao.cn/questions/topics/:id`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/lanqiao/questions/2",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "questions.ts",
  "maintainers": [
    "huhuhang"
  ],
  "name": "技术社区",
  "parameters": {
    "id": "topic_id 主题 `id` 可在社区板块 URL 中找到"
  },
  "path": "/questions/:id",
  "radar": [
    {
      "source": [
        "lanqiao.cn/questions/",
        "lanqiao.cn/questions/topics/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "lanqiao.cn/questions/"
}
```
