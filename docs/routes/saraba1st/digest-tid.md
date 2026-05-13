# Saraba1st - 论坛摘要

## Coverage
`index-only`

## Route
- Namespace: `saraba1st`
- Namespace Name: `Saraba1st`
- Route Path: `/digest/:tid`
- Route Name: `论坛摘要`
- Example: `/saraba1st/digest/forum-6-1`
- URL: `stage1st.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `shinemoon`
- Source Location: `digest.tsx`
- Source Module: `() => import('@/routes/saraba1st/digest.tsx')`

## Description
版面网址如果为 `https://stage1st.com/2b/forum-6-1.html` 那么论坛 id 就是 `forum-6-1`。

## Parameters
- `tid`: 论坛 id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "版面网址如果为 `https://stage1st.com/2b/forum-6-1.html` 那么论坛 id 就是 `forum-6-1`。",
  "example": "/saraba1st/digest/forum-6-1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "digest.tsx",
  "maintainers": [
    "shinemoon"
  ],
  "module": "() => import('@/routes/saraba1st/digest.tsx')",
  "name": "论坛摘要",
  "parameters": {
    "tid": "论坛 id"
  },
  "path": "/digest/:tid"
}
```
