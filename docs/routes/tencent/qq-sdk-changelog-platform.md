# 腾讯 - 更新日志

## Coverage
`index-only`

## Route
- Namespace: `tencent`
- Namespace Name: `腾讯`
- Route Path: `/qq/sdk/changelog/:platform`
- Route Name: `更新日志`
- Example: `/tencent/qq/sdk/changelog/iOS`
- URL: `tencent.com`
- Language: `zh-CN`
- Categories: `program-update`
- Maintainers: `nuomi1`
- Source Location: `qq/sdk/changelog.ts`
- Source Module: `() => import('@/routes/tencent/qq/sdk/changelog.ts')`

## Description
_None_

## Parameters
- `platform`: 平台，iOS / Android


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
    "program-update"
  ],
  "example": "/tencent/qq/sdk/changelog/iOS",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "qq/sdk/changelog.ts",
  "maintainers": [
    "nuomi1"
  ],
  "module": "() => import('@/routes/tencent/qq/sdk/changelog.ts')",
  "name": "更新日志",
  "parameters": {
    "platform": "平台，iOS / Android"
  },
  "path": "/qq/sdk/changelog/:platform"
}
```
