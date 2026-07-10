# 全民健康网 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `qm120`
- Namespace Name: `全民健康网`
- Route Path: `/qm120/news/:category?`
- Route Name: `新闻`
- Example: `/qm120/news`
- URL: `qm120.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

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
  "heat": 2,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
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
  "topFeeds": [
    {
      "description": "健康焦点 - 全民健康网 - Powered by RSSHub",
      "errorAt": "2026-04-12T08:52:16.871Z",
      "errorMessage": "[GET] \"http://www.qm120.com/news/jdxw\": 403 Forbidden\n",
      "id": "73954279631099904",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.qm120.com/news/jdxw",
      "title": "健康焦点 - 全民健康网",
      "type": "feed",
      "url": "rsshub://qm120/news"
    }
  ],
  "url": "qm120.com/"
}
```
