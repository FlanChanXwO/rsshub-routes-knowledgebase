# 西南交通大学 - 教务网

## Coverage
`index-only`

## Route
- Namespace: `swjtu`
- Namespace Name: `西南交通大学`
- Route Path: `/swjtu/jwc`
- Route Name: `教务网`
- Example: `/swjtu/jwc`
- URL: `jwc.swjtu.edu.cn/vatuu/WebAction`
- Language: `_None_`
- Categories: `university`
- Maintainers: `mobyw`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `jwc.swjtu.edu.cn/vatuu/WebAction`
  - `jwc.swjtu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/swjtu/jwc",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "jwc.ts",
  "maintainers": [
    "mobyw"
  ],
  "name": "教务网",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.swjtu.edu.cn/vatuu/WebAction",
        "jwc.swjtu.edu.cn/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "西南交大-教务网通知 - Powered by RSSHub",
      "errorAt": "2026-02-27T20:33:12.205Z",
      "errorMessage": "[GET] \"http://jwc.swjtu.edu.cn/vatuu/WebAction?setAction=newsList\": <no response> fetch failed\n",
      "id": "72512219481102339",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://jwc.swjtu.edu.cn/vatuu/WebAction?setAction=newsList",
      "title": "西南交大-教务网通知",
      "type": "feed",
      "url": "rsshub://swjtu/jwc"
    }
  ],
  "url": "jwc.swjtu.edu.cn/vatuu/WebAction"
}
```
