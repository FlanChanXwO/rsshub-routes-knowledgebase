# Hangzhou People's Government - 最新文件

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `Hangzhou People's Government`
- Route Path: `/gov/zhengce/wenjian/:pcodeJiguan?`
- Route Name: `最新文件`
- Example: `/gov/zhengce/wenjian`
- URL: `www.gov.cn/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `ciaranchen`
- Source Location: `zhengce/wenjian.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `pcodeJiguan`: 文种分类。国令、国发、国函、国发明电、国办发、国办函、国办发明电、其他


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
  - `www.gov.cn/`
- `target`: `/zhengce/wenjian`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/zhengce/wenjian",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "zhengce/wenjian.ts",
  "maintainers": [
    "ciaranchen"
  ],
  "name": "最新文件",
  "parameters": {
    "pcodeJiguan": "文种分类。国令、国发、国函、国发明电、国办发、国办函、国办发明电、其他"
  },
  "path": "/zhengce/wenjian/:pcodeJiguan?",
  "radar": [
    {
      "source": [
        "www.gov.cn/"
      ],
      "target": "/zhengce/wenjian"
    }
  ],
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-15T12:16:26.855Z",
      "errorMessage": "[GET] \"http://sousuo.gov.cn/list.htm?n=20&sort=pubtime&t=paper&pcodeJiguan\": <no response> fetch failed\n",
      "id": "145767488928582665",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://gov/zhengce/wenjian"
    }
  ],
  "url": "www.gov.cn/"
}
```
