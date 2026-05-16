# 西北师范大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `nwnu`
- Namespace Name: `西北师范大学`
- Route Path: `/nwnu/department/academic-affairs/:column`
- Route Name: `教务处`
- Example: `/department/academic-affairs/tzgg`
- URL: `www.nwnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `PrinOrange`
- Source Location: `routes/department/academic-affairs.ts`
- Source Module: `_None_`

## Description
| column | 标题     | 描述                     |
| ------ | -------- | ------------------------ |
| tzgg   | 通知公告 | 西北师范大学教务通知公告 |
| jwkx   | 教务快讯 | 西北师范大学教务快讯     |

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportRadar`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `jwc.nwnu.edu.cn/:column/list.htm`
- `target`: `/department/academic-affairs/:column`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| column | 标题     | 描述                     |\n| ------ | -------- | ------------------------ |\n| tzgg   | 通知公告 | 西北师范大学教务通知公告 |\n| jwkx   | 教务快讯 | 西北师范大学教务快讯     |",
  "example": "/department/academic-affairs/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1,
  "location": "routes/department/academic-affairs.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "name": "教务处",
  "path": "/department/academic-affairs/:column",
  "radar": [
    {
      "source": [
        "jwc.nwnu.edu.cn/:column/list.htm"
      ],
      "target": "/department/academic-affairs/:column"
    }
  ],
  "topFeeds": [
    {
      "description": "西北师范大学教务处通知公告 - Powered by RSSHub",
      "errorAt": "2025-10-29T13:20:46.613Z",
      "errorMessage": "[GET] \"https://jwc.nwnu.edu.cn/tzgg/list.htm\": 412 Precondition Failed\n",
      "id": "130747779142325248",
      "image": "https://www.nwnu.edu.cn/_upload/tpl/02/d9/729/template729/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://jwc.nwnu.edu.cn/tzgg/list.htm",
      "title": "通知公告",
      "type": "feed",
      "url": "rsshub://nwnu/department/academic-affairs/tzgg"
    }
  ]
}
```
