# 中国海洋大学 - 选课信息教务通知

## Coverage
`index-only`

## Route
- Namespace: `ouc`
- Namespace Name: `中国海洋大学`
- Route Path: `/ouc/jwgl`
- Route Name: `选课信息教务通知`
- Example: `/ouc/jwgl`
- URL: `jwgl.ouc.edu.cn/cas/login.action`
- Language: `_None_`
- Categories: `university`
- Maintainers: `3401797899`
- Source Location: `jwgl.ts`
- Source Module: `_None_`

## Description
::: warning
由于选课通知仅允许校园网访问，需自行部署。
:::

## Parameters
_None_


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
  - `jwgl.ouc.edu.cn/cas/login.action`
  - `jwgl.ouc.edu.cn/public/SchoolNotice.jsp`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: warning\n由于选课通知仅允许校园网访问，需自行部署。\n:::",
  "example": "/ouc/jwgl",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwgl.ts",
  "maintainers": [
    "3401797899"
  ],
  "name": "选课信息教务通知",
  "parameters": {},
  "path": "/jwgl",
  "radar": [
    {
      "source": [
        "jwgl.ouc.edu.cn/cas/login.action",
        "jwgl.ouc.edu.cn/public/SchoolNotice.jsp"
      ]
    }
  ],
  "topFeeds": [],
  "url": "jwgl.ouc.edu.cn/cas/login.action"
}
```
