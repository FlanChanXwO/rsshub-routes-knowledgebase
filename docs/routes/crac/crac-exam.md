# 中国无线电协会业余无线电分会 - 考试信息

## Coverage
`index-only`

## Route
- Namespace: `crac`
- Namespace Name: `中国无线电协会业余无线电分会`
- Route Path: `/crac/exam`
- Route Name: `考试信息`
- Example: `/crac/exam`
- URL: `www.crac.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `admxj`
- Source Location: `exam.tsx`
- Source Module: `_None_`

## Description
_None_

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
  - `www.crac.org.cn/*`
- `target`: `/exam`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/crac/exam",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "exam.tsx",
  "maintainers": [
    "admxj"
  ],
  "name": "考试信息",
  "path": "/exam",
  "radar": [
    {
      "source": [
        "www.crac.org.cn/*"
      ],
      "target": "/exam"
    }
  ],
  "topFeeds": [
    {
      "description": "考试信息-中国无线电协会业余无线电分会 - Powered by RSSHub",
      "errorAt": "2026-02-14T01:57:22.686Z",
      "errorMessage": "[POST] \"http://82.157.138.16:8091/CRAC/app/exam_advice/examAdviceList\": <no response> fetch failed\n",
      "id": "138468429736494080",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://82.157.138.16:8091/CRAC/crac/pages/list_examMsg.html",
      "title": "考试信息-中国无线电协会业余无线电分会",
      "type": "feed",
      "url": "rsshub://crac/exam"
    }
  ]
}
```
