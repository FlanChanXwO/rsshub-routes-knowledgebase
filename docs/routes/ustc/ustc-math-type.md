# 中国科学技术大学 - 数学科学学院

## Coverage
`index-only`

## Route
- Namespace: `ustc`
- Namespace Name: `中国科学技术大学`
- Route Path: `/ustc/math/:type?`
- Route Name: `数学科学学院`
- Example: `/ustc/math/tzgg`
- URL: `math.ustc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ne0-wu`
- Source Location: `math.ts`
- Source Module: `_None_`

## Description
| 学院新闻 | 通知公告 | 学术交流 | 学术报告 |
| -------- | -------- | -------- | -------- |
| xyxw     | tzgg     | xsjl     | xsbg     |

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
  - `math.ustc.edu.cn/`
- `target`: `/math`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院新闻 | 通知公告 | 学术交流 | 学术报告 |\n| -------- | -------- | -------- | -------- |\n| xyxw     | tzgg     | xsjl     | xsbg     |",
  "example": "/ustc/math/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "math.ts",
  "maintainers": [
    "ne0-wu"
  ],
  "name": "数学科学学院",
  "parameters": {
    "type": "分类，见下表，默认为通知公告"
  },
  "path": "/math/:type?",
  "radar": [
    {
      "source": [
        "math.ustc.edu.cn/"
      ],
      "target": "/math"
    }
  ],
  "topFeeds": [
    {
      "description": "中国科学技术大学数学科学学院 - 通知公告 - Powered by RSSHub",
      "errorAt": "2025-11-04T01:54:03.079Z",
      "errorMessage": "[GET] \"https://math.ustc.edu.cn/tzgg/list.htm\": <no response> fetch failed\n",
      "id": "155112954040188928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://math.ustc.edu.cn/tzgg/list.htm",
      "title": "中国科学技术大学数学科学学院 - 通知公告",
      "type": "feed",
      "url": "rsshub://ustc/math/tzgg"
    }
  ],
  "url": "math.ustc.edu.cn/"
}
```
