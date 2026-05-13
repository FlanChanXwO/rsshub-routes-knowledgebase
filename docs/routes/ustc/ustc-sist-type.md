# 中国科学技术大学 - 信息科学技术学院

## Coverage
`index-only`

## Route
- Namespace: `ustc`
- Namespace Name: `中国科学技术大学`
- Route Path: `/ustc/sist/:type?`
- Route Name: `信息科学技术学院`
- Example: `/ustc/sist/tzgg`
- URL: `sist.ustc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `jasongzy`
- Source Location: `sist.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 招生工作 |
| -------- | -------- |
| tzgg     | zsgz     |

## Parameters
- `type`: 分类，见下表，默认为通知公告


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
  - `sist.ustc.edu.cn/`
- `target`: `/sist`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 招生工作 |\n| -------- | -------- |\n| tzgg     | zsgz     |",
  "example": "/ustc/sist/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "sist.ts",
  "maintainers": [
    "jasongzy"
  ],
  "name": "信息科学技术学院",
  "parameters": {
    "type": "分类，见下表，默认为通知公告"
  },
  "path": "/sist/:type?",
  "radar": [
    {
      "source": [
        "sist.ustc.edu.cn/"
      ],
      "target": "/sist"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中国科学技术大学信息科学技术学院 - 通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78285608501653504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sist.ustc.edu.cn/5142/list.htm",
      "title": "中国科学技术大学信息科学技术学院 - 通知公告",
      "type": "feed",
      "url": "rsshub://ustc/sist/tzgg"
    }
  ],
  "url": "sist.ustc.edu.cn/"
}
```
