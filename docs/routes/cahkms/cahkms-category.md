# 全国港澳研究会 - 分类

## Coverage
`index-only`

## Route
- Namespace: `cahkms`
- Namespace Name: `全国港澳研究会`
- Route Path: `/cahkms/:category?`
- Route Name: `分类`
- Example: `/cahkms`
- URL: `cahkms.org/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| 关于我们 | 港澳新闻 | 重要新闻 | 顾问点评、会员观点 | 专题汇总 |
| -------- | -------- | -------- | ------------------ | -------- |
| 01       | 02       | 03       | 04                 | 05       |

| 港澳时评 | 图片新闻 | 视频中心 | 港澳研究 | 最新书讯 | 研究资讯 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 06       | 07       | 08       | 09       | 10       | 11       |

## Parameters
- `category`: 分类，见下表，默认为重要新闻


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
  - `cahkms.org/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 关于我们 | 港澳新闻 | 重要新闻 | 顾问点评、会员观点 | 专题汇总 |\n| -------- | -------- | -------- | ------------------ | -------- |\n| 01       | 02       | 03       | 04                 | 05       |\n\n| 港澳时评 | 图片新闻 | 视频中心 | 港澳研究 | 最新书讯 | 研究资讯 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| 06       | 07       | 08       | 09       | 10       | 11       |",
  "example": "/cahkms",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为重要新闻"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "cahkms.org/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "重要新闻 - 全国港澳研究会 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73954052480943104",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.cahkms.org/HKMAC/indexMac/getRightList?dm=03&page=1&countPage=10",
      "title": "重要新闻 - 全国港澳研究会",
      "type": "feed",
      "url": "rsshub://cahkms"
    }
  ],
  "url": "cahkms.org/"
}
```
