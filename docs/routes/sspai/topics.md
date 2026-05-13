# 少数派 sspai - 专题

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/topics`
- Route Name: `专题`
- Example: `/sspai/topics`
- URL: `sspai.com/topics`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `SunShinenny`
- Source Location: `topics.ts`
- Source Module: `() => import('@/routes/sspai/topics.ts')`

## Description
此为专题广场更新提示 => 集合型而非单篇文章。与下方 "专题内文章更新" 存在明显区别！

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
  - `sspai.com/topics`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "此为专题广场更新提示 => 集合型而非单篇文章。与下方 \"专题内文章更新\" 存在明显区别！",
  "example": "/sspai/topics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topics.ts",
  "maintainers": [
    "SunShinenny"
  ],
  "module": "() => import('@/routes/sspai/topics.ts')",
  "name": "专题",
  "parameters": {},
  "path": "/topics",
  "radar": [
    {
      "source": [
        "sspai.com/topics"
      ]
    }
  ],
  "url": "sspai.com/topics"
}
```
