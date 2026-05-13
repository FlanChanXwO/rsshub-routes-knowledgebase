# 虎嗅 - 源流

## Coverage
`index-only`

## Route
- Namespace: `huxiu`
- Namespace Name: `虎嗅`
- Route Path: `/club/:id`
- Route Name: `源流`
- Example: `/huxiu/club/1161`
- URL: `huxiu.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk, TimoYoung`
- Source Location: `club.ts`
- Source Module: `() => import('@/routes/huxiu/club.ts')`

## Description
更多源流请参见 [源流](https://www.huxiu.com/club)

## Parameters
- `id`: 源流 id，可在对应源流页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "更多源流请参见 [源流](https://www.huxiu.com/club)",
  "example": "/huxiu/club/1161",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "club.ts",
  "maintainers": [
    "nczitzk",
    "TimoYoung"
  ],
  "module": "() => import('@/routes/huxiu/club.ts')",
  "name": "源流",
  "parameters": {
    "id": "源流 id，可在对应源流页 URL 中找到"
  },
  "path": "/club/:id"
}
```
