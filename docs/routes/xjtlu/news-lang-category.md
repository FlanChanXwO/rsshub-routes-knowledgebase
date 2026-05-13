# Xi'an Jiaotong-Liverpool University - News

## Coverage
`index-only`

## Route
- Namespace: `xjtlu`
- Namespace Name: `Xi'an Jiaotong-Liverpool University`
- Route Path: `/news/:lang?/:category?`
- Route Name: `News`
- Example: `/xjtlu/news/en/technology`
- URL: `www.xjtlu.edu.cn/en/news`
- Language: `en`
- Categories: `university`
- Maintainers: `Circloud`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/xjtlu/news.ts')`

## Description
Categories:

| Category | English Name | Chinese Name |
| -------- | ------------ | ------------ |
| `all` | All | 全部 |
| `anniversary` | XJTLU 20th Anniversary | 西浦20周年 |
| `technology` | Science and Technology | 科技 |
| `business` | Business | 商业管理 |
| `environment` | Built Environment | 建筑环境 |
| `humanities` | Humanities and Social Sciences | 人文社科 |
| `community` | Community | 校园与社区 |
| `about` | About XJTLU | 要闻聚焦 |
| `stories` | XJTLU Stories | 招生专区 |

## Parameters
- `lang`: Language, `en` or `zh`, default: `en`
- `category`: Category, see table below, default: `all`


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
  - `www.xjtlu.edu.cn/:lang/about/news/all-news`
  - `www.xjtlu.edu.cn/:lang/news`
- `target`: `/news/:lang`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "Categories:\n\n| Category | English Name | Chinese Name |\n| -------- | ------------ | ------------ |\n| `all` | All | 全部 |\n| `anniversary` | XJTLU 20th Anniversary | 西浦20周年 |\n| `technology` | Science and Technology | 科技 |\n| `business` | Business | 商业管理 |\n| `environment` | Built Environment | 建筑环境 |\n| `humanities` | Humanities and Social Sciences | 人文社科 |\n| `community` | Community | 校园与社区 |\n| `about` | About XJTLU | 要闻聚焦 |\n| `stories` | XJTLU Stories | 招生专区 |",
  "example": "/xjtlu/news/en/technology",
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
    "Circloud"
  ],
  "module": "() => import('@/routes/xjtlu/news.ts')",
  "name": "News",
  "parameters": {
    "category": "Category, see table below, default: `all`",
    "lang": "Language, `en` or `zh`, default: `en`"
  },
  "path": "/news/:lang?/:category?",
  "radar": [
    {
      "source": [
        "www.xjtlu.edu.cn/:lang/about/news/all-news",
        "www.xjtlu.edu.cn/:lang/news"
      ],
      "target": "/news/:lang"
    }
  ],
  "url": "www.xjtlu.edu.cn/en/news"
}
```
