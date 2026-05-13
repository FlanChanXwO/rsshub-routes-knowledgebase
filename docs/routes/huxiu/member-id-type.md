# 虎嗅 - 用户

## Coverage
`index-only`

## Route
- Namespace: `huxiu`
- Namespace Name: `虎嗅`
- Route Path: `/member/:id/:type?`
- Route Name: `用户`
- Example: `/huxiu/member/2313050`
- URL: `huxiu.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `member.ts`
- Source Module: `() => import('@/routes/huxiu/member.ts')`

## Description
| TA 的文章 | TA 的 24 小时 |
| --------- | ------------- |
| article   | moment        |

## Parameters
- `id`: 用户 id，可在对应用户页 URL 中找到


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
  "description": "| TA 的文章 | TA 的 24 小时 |\n| --------- | ------------- |\n| article   | moment        |",
  "example": "/huxiu/member/2313050",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "member.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/huxiu/member.ts')",
  "name": "用户",
  "parameters": {
    "id": "用户 id，可在对应用户页 URL 中找到"
  },
  "path": [
    "/author/:id/:type?",
    "/member/:id/:type?"
  ]
}
```
