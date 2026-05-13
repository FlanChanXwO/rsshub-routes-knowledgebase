# 上海外国语大学 - 上外新闻

## Coverage
`index-only`

## Route
- Namespace: `shisu`
- Namespace Name: `上海外国语大学`
- Route Path: `/news/:section`
- Route Name: `上外新闻`
- Example: `/shisu/news/news`
- URL: `shisu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Duuckjing`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/shisu/news.ts')`

## Description
| 首页 | 特稿    | 学术      | 教学       | 国际          | 校园   | 人物   | 视讯       | 公告   |
| ---- | ------- | --------- | ---------- | ------------- | ------ | ------ | ---------- | ------ |
| news | gazette | research- | academics- | international | campus | people | multimedia | notice |

## Parameters
- `section`: 主站的新闻类别


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
  - `news.shisu.edu.cn/:section/index.html`
- `target`: `/news/:section`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 首页 | 特稿    | 学术      | 教学       | 国际          | 校园   | 人物   | 视讯       | 公告   |\n| ---- | ------- | --------- | ---------- | ------------- | ------ | ------ | ---------- | ------ |\n| news | gazette | research- | academics- | international | campus | people | multimedia | notice |",
  "example": "/shisu/news/news",
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
    "Duuckjing"
  ],
  "module": "() => import('@/routes/shisu/news.ts')",
  "name": "上外新闻",
  "parameters": {
    "section": "主站的新闻类别"
  },
  "path": "/news/:section",
  "radar": [
    {
      "source": [
        "news.shisu.edu.cn/:section/index.html"
      ],
      "target": "/news/:section"
    }
  ]
}
```
