# 全民健康网 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `qm120`
- Namespace Name: `全民健康网`
- Route Path: `/news/:category?`
- Route Name: `新闻`
- Example: `/qm120/news`
- URL: `qm120.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/qm120/news.ts')`

## Description
| 健康焦点 | 行业动态 | 医学前沿 | 法规动态 |
| -------- | -------- | -------- | -------- |
| jdxw     | hydt     | yxqy     | fgdt     |

| 食品安全 | 医疗事故 | 医药会展 | 医药信息 |
| -------- | -------- | -------- | -------- |
| spaq     | ylsg     | yyhz     | yyxx     |

| 新闻专题 | 行业新闻 |
| -------- | -------- |
| zhuanti  | xyxw     |

## Parameters
- `category`: 分类，见下表，默认为健康焦点


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
  - `qm120.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 健康焦点 | 行业动态 | 医学前沿 | 法规动态 |\n| -------- | -------- | -------- | -------- |\n| jdxw     | hydt     | yxqy     | fgdt     |\n\n| 食品安全 | 医疗事故 | 医药会展 | 医药信息 |\n| -------- | -------- | -------- | -------- |\n| spaq     | ylsg     | yyhz     | yyxx     |\n\n| 新闻专题 | 行业新闻 |\n| -------- | -------- |\n| zhuanti  | xyxw     |",
  "example": "/qm120/news",
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
  "module": "() => import('@/routes/qm120/news.ts')",
  "name": "新闻",
  "parameters": {
    "category": "分类，见下表，默认为健康焦点"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "qm120.com/"
      ]
    }
  ],
  "url": "qm120.com/"
}
```
