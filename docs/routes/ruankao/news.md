# 中国计算机职业技术资格考试 - 软考动态

## Coverage
`index-only`

## Route
- Namespace: `ruankao`
- Namespace Name: `中国计算机职业技术资格考试`
- Route Path: `/news`
- Route Name: `软考动态`
- Example: `/ruankao/news`
- URL: `www.ruankao.org.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `PrinOrange`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/ruankao/news.ts')`

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
- `title`: `计算机职业技术资格考试（软考）动态`
- `source`:
  - `www.ruankao.org.cn/index/work`
  - `www.ruankao.org.cn`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "**注意：** 官方网站限制了国外网络请求，可能需要通过部署在中国大陆内的 RSSHub 实例访问。",
  "example": "/ruankao/news",
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
  "module": "() => import('@/routes/ruankao/news.ts')",
  "name": "软考动态",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.ruankao.org.cn/index/work",
        "www.ruankao.org.cn"
      ],
      "target": "/news",
      "title": "计算机职业技术资格考试（软考）动态"
    }
  ]
}
```
