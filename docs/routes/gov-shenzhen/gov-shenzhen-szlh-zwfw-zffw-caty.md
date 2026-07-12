# 深圳市人民政府 - 罗湖区人民政府 政务服务

## Coverage
`index-only`

## Route
- Namespace: `gov/shenzhen`
- Namespace Name: `深圳市人民政府`
- Route Path: `/gov/shenzhen/szlh/zwfw/zffw/:caty`
- Route Name: `罗湖区人民政府 政务服务`
- Example: `/gov/shenzhen/szlh/zwfw/zffw/tzgg`
- URL: `www.sz.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `lonn`
- Source Location: `szlh/index.ts`
- Source Module: `_None_`

## Description
| 通知公告 |
| :------: |
|   tzgg   |

## Parameters
- `caty`: 信息类别


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
  - `szlh.gov.cn/zwfw/zffw/:caty`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告 |\n| :------: |\n|   tzgg   |",
  "example": "/gov/shenzhen/szlh/zwfw/zffw/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "szlh/index.ts",
  "maintainers": [
    "lonn"
  ],
  "name": "罗湖区人民政府 政务服务",
  "parameters": {
    "caty": "信息类别"
  },
  "path": "/szlh/zwfw/zffw/:caty",
  "radar": [
    {
      "source": [
        "szlh.gov.cn/zwfw/zffw/:caty"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "深圳市罗湖区人民政府 - 通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "177353249662572544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.szlh.gov.cn/zwfw/zffw/tzgg/",
      "title": "深圳市罗湖区人民政府 - 通知公告",
      "type": "feed",
      "url": "rsshub://gov/shenzhen/szlh/zwfw/zffw/tzgg"
    }
  ]
}
```
