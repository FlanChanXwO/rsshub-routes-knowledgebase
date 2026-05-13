# 中国计算机学会 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `ccf`
- Namespace Name: `中国计算机学会`
- Route Path: `/news/:category?`
- Route Name: `新闻`
- Example: `/ccf/news`
- URL: `ccf.org.cn`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/ccf/news.ts')`

## Description
| CCF 新闻    | CCF 聚焦 | ACM 信息  |
| ----------- | -------- | --------- |
| Media_list | Focus    | ACM_News |

## Parameters
- `category`: 分类，见下表，默认为 CCF 新闻


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
  - `ccf.org.cn/:category`
  - `ccf.org.cn/`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| CCF 新闻    | CCF 聚焦 | ACM 信息  |\n| ----------- | -------- | --------- |\n| Media_list | Focus    | ACM_News |",
  "example": "/ccf/news",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/ccf/news.ts')",
  "name": "新闻",
  "parameters": {
    "category": "分类，见下表，默认为 CCF 新闻"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "ccf.org.cn/:category",
        "ccf.org.cn/"
      ],
      "target": "/news/:category"
    }
  ]
}
```
