# Google - Update

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/doodles/:language?`
- Route Name: `Update`
- Example: `/google/doodles/zh-CN`
- URL: `www.google.com`
- Language: `en`
- Categories: `picture`
- Maintainers: `xyqfer`
- Source Location: `doodles.ts`
- Source Module: `() => import('@/routes/google/doodles.ts')`

## Description
_None_

## Parameters
- `language`: Language, default to `zh-CN`, for other language values, you can get it from [Google Doodles official website](https://www.google.com/doodles)


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
    "picture"
  ],
  "example": "/google/doodles/zh-CN",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "doodles.ts",
  "maintainers": [
    "xyqfer"
  ],
  "module": "() => import('@/routes/google/doodles.ts')",
  "name": "Update",
  "parameters": {
    "language": "Language, default to `zh-CN`, for other language values, you can get it from [Google Doodles official website](https://www.google.com/doodles)"
  },
  "path": "/doodles/:language?",
  "view": 2
}
```
