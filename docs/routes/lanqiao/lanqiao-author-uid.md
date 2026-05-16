# 蓝桥云课 - 作者发布的课程

## Coverage
`index-only`

## Route
- Namespace: `lanqiao`
- Namespace Name: `蓝桥云课`
- Route Path: `/lanqiao/author/:uid`
- Route Name: `作者发布的课程`
- Example: `/lanqiao/author/1701267`
- URL: `lanqiao.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `huhuhang`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 作者 `uid` 可在作者主页 URL 中找到


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
  - `lanqiao.cn/users/:uid`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/lanqiao/author/1701267",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "author.ts",
  "maintainers": [
    "huhuhang"
  ],
  "name": "作者发布的课程",
  "parameters": {
    "uid": "作者 `uid` 可在作者主页 URL 中找到"
  },
  "path": "/author/:uid",
  "radar": [
    {
      "source": [
        "lanqiao.cn/users/:uid"
      ]
    }
  ],
  "topFeeds": []
}
```
