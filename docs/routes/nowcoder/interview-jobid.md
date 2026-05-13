# 牛客网 - 牛客面试经验

## Coverage
`index-only`

## Route
- Namespace: `nowcoder`
- Namespace Name: `牛客网`
- Route Path: `/interview/:jobId`
- Route Name: `牛客面试经验`
- Example: `/nowcoder/interview/11200`
- URL: `nowcoder.com/`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `xia0ne`
- Source Location: `interview.ts`
- Source Module: `() => import('@/routes/nowcoder/interview.ts')`

## Description
牛客面试经验

## Parameters
- `jobId`: 岗位 ID，如 11200（全部）、11002（Java）


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
  - `www.nowcoder.com/interview/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "牛客面试经验",
  "example": "/nowcoder/interview/11200",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "interview.ts",
  "maintainers": [
    "xia0ne"
  ],
  "module": "() => import('@/routes/nowcoder/interview.ts')",
  "name": "牛客面试经验",
  "parameters": {
    "jobId": "岗位 ID，如 11200（全部）、11002（Java）"
  },
  "path": "/interview/:jobId",
  "radar": [
    {
      "source": [
        "www.nowcoder.com/interview/"
      ]
    }
  ],
  "url": "nowcoder.com/"
}
```
