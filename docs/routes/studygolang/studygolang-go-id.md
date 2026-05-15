# Go 语言中文网 - 板块

## Coverage
`index-only`

## Route
- Namespace: `studygolang`
- Namespace Name: `Go 语言中文网`
- Route Path: `/studygolang/go/:id?`
- Route Name: `板块`
- Example: `/studygolang/go/daily`
- URL: `studygolang.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `go.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 板块 id，默认为周刊


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
  - `studygolang.com/go/:id`
  - `studygolang.com/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/studygolang/go/daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 319,
  "location": "go.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "板块",
  "parameters": {
    "id": "板块 id，默认为周刊"
  },
  "path": "/go/:id?",
  "radar": [
    {
      "source": [
        "studygolang.com/go/:id",
        "studygolang.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Go语言中文网 - Go周刊 - Powered by RSSHub",
      "errorAt": "2026-05-09T01:03:14.101Z",
      "errorMessage": "[GET] \"https://studygolang.com/go/weekly\": 502 Bad Gateway\n[GET] \"https://studygolang.com/go/weekly\": 502 Bad Gateway\n[GET] \"https://studygolang.com/go/weekly\": 502 Bad Gateway\n",
      "id": "56597687648785408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://studygolang.com/go/weekly",
      "title": "Go语言中文网 - Go周刊",
      "type": "feed",
      "url": "rsshub://studygolang/go"
    },
    {
      "description": "Go语言中文网 - 每日一学 - Powered by RSSHub",
      "errorAt": "2026-05-11T11:28:30.764Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://studygolang.com/go/daily\": 502 Bad Gateway\n",
      "id": "54846819419389955",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://studygolang.com/go/daily",
      "title": "Go语言中文网 - 每日一学",
      "type": "feed",
      "url": "rsshub://studygolang/go/daily"
    }
  ]
}
```
