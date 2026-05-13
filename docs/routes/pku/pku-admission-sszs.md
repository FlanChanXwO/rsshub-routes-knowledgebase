# 北京大学 - 研究生招生网

## Coverage
`index-only`

## Route
- Namespace: `pku`
- Namespace Name: `北京大学`
- Route Path: `/pku/admission/sszs`
- Route Name: `研究生招生网`
- Example: `/pku/admission/sszs`
- URL: `admission.pku.edu.cn/zsxx/sszs/index.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `pkuyjs`
- Source Location: `pkuyjs.ts`
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
  - `admission.pku.edu.cn/zsxx/sszs/index.htm`
  - `admission.pku.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/pku/admission/sszs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "pkuyjs.ts",
  "maintainers": [
    "pkuyjs"
  ],
  "name": "研究生招生网",
  "parameters": {},
  "path": "/admission/sszs",
  "radar": [
    {
      "source": [
        "admission.pku.edu.cn/zsxx/sszs/index.htm",
        "admission.pku.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "北京大学研究生院通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72674174547415040",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://admission.pku.edu.cn/zsxx/sszs/index.htm",
      "title": "硕士招生 - 北京大学研究生招生网",
      "type": "feed",
      "url": "rsshub://pku/admission/sszs"
    }
  ],
  "url": "admission.pku.edu.cn/zsxx/sszs/index.htm"
}
```
