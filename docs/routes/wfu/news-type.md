# 潍坊学院 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `wfu`
- Namespace Name: `潍坊学院`
- Route Path: `/news/:type?`
- Route Name: `新闻`
- Example: `/wfu/news/wyyw`
- URL: `news.wfu.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `cccht`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/wfu/news.ts')`

## Description
| **内容** | **参数** |
| :------: | :------: |
| 潍院要闻 |   wyyw   |
| 综合新闻 |   zhxw   |
| 学术纵横 |   xszh   |

## Parameters
- `type`: 分类，默认为 `wyyw`，具体参数见下表


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
  - `news.wfu.edu.cn/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| **内容** | **参数** |\n| :------: | :------: |\n| 潍院要闻 |   wyyw   |\n| 综合新闻 |   zhxw   |\n| 学术纵横 |   xszh   |",
  "example": "/wfu/news/wyyw",
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
    "cccht"
  ],
  "module": "() => import('@/routes/wfu/news.ts')",
  "name": "新闻",
  "parameters": {
    "type": "分类，默认为 `wyyw`，具体参数见下表"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "news.wfu.edu.cn/"
      ],
      "target": "/news"
    }
  ],
  "url": "news.wfu.edu.cn/"
}
```
