# 北京邮电大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `bupt`
- Namespace Name: `北京邮电大学`
- Route Path: `/bupt/jwc/:type`
- Route Name: `教务处`
- Example: `/bupt/jwc/tzgg`
- URL: `jwc.bupt.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Yoruet`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"description": "信息类型，可选值：tzgg（通知公告），xwzx（新闻资讯）", "optional": false, "type": "string"}


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
  - `jwc.bupt.edu.cn/tzgg1.htm`
- `target`: `/jwc/tzgg`
### Rule 2
- `source`:
  - `jwc.bupt.edu.cn/xwzx2.htm`
- `target`: `/jwc/xwzx`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/bupt/jwc/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "jwc.ts",
  "maintainers": [
    "Yoruet"
  ],
  "name": "教务处",
  "parameters": {
    "type": {
      "description": "信息类型，可选值：tzgg（通知公告），xwzx（新闻资讯）",
      "optional": false,
      "type": "string"
    }
  },
  "path": "/jwc/:type",
  "radar": [
    {
      "source": [
        "jwc.bupt.edu.cn/tzgg1.htm"
      ],
      "target": "/jwc/tzgg"
    },
    {
      "source": [
        "jwc.bupt.edu.cn/xwzx2.htm"
      ],
      "target": "/jwc/xwzx"
    }
  ],
  "topFeeds": [
    {
      "description": "北京邮电大学教务处 - 通知公告 - Powered by RSSHub",
      "errorAt": "2025-06-17T10:59:36.247Z",
      "errorMessage": "[GET] \"https://jwc.bupt.edu.cn/tzgg1.htm\": 412 Precondition Failed\n",
      "id": "60007690824851456",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.bupt.edu.cn/tzgg1.htm",
      "title": "北京邮电大学教务处 - 通知公告",
      "type": "feed",
      "url": "rsshub://bupt/jwc/tzgg"
    },
    {
      "description": "北京邮电大学教务处 - 新闻资讯 - Powered by RSSHub",
      "errorAt": "2024-12-08T04:51:10.859Z",
      "errorMessage": "[GET] \"https://jwc.bupt.edu.cn/xwzx2.htm\": 412 Precondition Failed\n",
      "id": "64946001225288704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.bupt.edu.cn/xwzx2.htm",
      "title": "北京邮电大学教务处 - 新闻资讯",
      "type": "feed",
      "url": "rsshub://bupt/jwc/xwzx"
    }
  ],
  "url": "jwc.bupt.edu.cn"
}
```
