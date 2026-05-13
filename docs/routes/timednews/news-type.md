# 时刻新闻 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `timednews`
- Namespace Name: `时刻新闻`
- Route Path: `/news/:type?`
- Route Name: `新闻`
- Example: `/timednews/news`
- URL: `timednews.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `linbuxiao`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/timednews/news.ts')`

## Description
子分类

| 全部 | 时政           | 财经    | 科技       | 社会   | 体娱   | 国际          | 美国 | 中国 | 欧洲   | 评论     |
| ---- | -------------- | ------- | ---------- | ------ | ------ | ------------- | ---- | ---- | ------ | -------- |
| all  | currentAffairs | finance | technology | social | sports | international | usa  | cn   | europe | comments |

## Parameters
- `type`: 子分类，见下表，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "子分类\n\n| 全部 | 时政           | 财经    | 科技       | 社会   | 体娱   | 国际          | 美国 | 中国 | 欧洲   | 评论     |\n| ---- | -------------- | ------- | ---------- | ------ | ------ | ------------- | ---- | ---- | ------ | -------- |\n| all  | currentAffairs | finance | technology | social | sports | international | usa  | cn   | europe | comments |",
  "example": "/timednews/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "linbuxiao"
  ],
  "module": "() => import('@/routes/timednews/news.ts')",
  "name": "新闻",
  "parameters": {
    "type": "子分类，见下表，默认为全部"
  },
  "path": "/news/:type?"
}
```
