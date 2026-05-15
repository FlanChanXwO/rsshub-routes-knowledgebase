# 深圳市罗湖区人民政府 - 上海市文旅局审批公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `深圳市罗湖区人民政府`
- Route Path: `/gov/sh/wgj/:page?`
- Route Name: `上海市文旅局审批公告`
- Example: `/gov/sh/wgj`
- URL: `wsbs.wgj.sh.gov.cn/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `gideonsenku`
- Source Location: `sh/wgj/wgj.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `page`: 页数，默认第 1 页


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
  - `wsbs.wgj.sh.gov.cn/`
- `target`: `/sh/wgj`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/sh/wgj",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "sh/wgj/wgj.tsx",
  "maintainers": [
    "gideonsenku"
  ],
  "name": "上海市文旅局审批公告",
  "parameters": {
    "page": "页数，默认第 1 页"
  },
  "path": [
    "/sh/wgj/:page?",
    "/shanghai/wgj/:page?"
  ],
  "radar": [
    {
      "source": [
        "wsbs.wgj.sh.gov.cn/"
      ],
      "target": "/sh/wgj"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "上海市文化和旅游局 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71029156450169856",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://wsbs.wgj.sh.gov.cn/shwgj_ywtb/core/web/welcome/index!toResultNotice.action",
      "title": "上海市文化和旅游局",
      "type": "feed",
      "url": "rsshub://gov/sh/wgj"
    }
  ],
  "url": "wsbs.wgj.sh.gov.cn/"
}
```
