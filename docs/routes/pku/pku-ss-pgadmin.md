# 北京大学 - 软件与微电子学院 - 硕士统考招生通知

## Coverage
`index-only`

## Route
- Namespace: `pku`
- Namespace Name: `北京大学`
- Route Path: `/pku/ss/pgadmin`
- Route Name: `软件与微电子学院 - 硕士统考招生通知`
- Example: `/pku/ss/pgadmin`
- URL: `ss.pku.edu.cn/admission/admbrochure/admission01`
- Language: `_None_`
- Categories: `university`
- Maintainers: `legr4ndk`
- Source Location: `ss/pg-admin.ts`
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
  - `ss.pku.edu.cn/admission/admbrochure/admission01`
  - `ss.pku.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/pku/ss/pgadmin",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "ss/pg-admin.ts",
  "maintainers": [
    "legr4ndk"
  ],
  "name": "软件与微电子学院 - 硕士统考招生通知",
  "parameters": {},
  "path": "/ss/pgadmin",
  "radar": [
    {
      "source": [
        "ss.pku.edu.cn/admission/admbrochure/admission01",
        "ss.pku.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "北京大学软件与微电子学院 - 硕士统考招生通知 - Powered by RSSHub",
      "errorAt": "2026-01-12T08:53:08.480Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "95692794489780224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ss.pku.edu.cn/admission/admbrochure/",
      "title": "北大软微-硕士统考招生",
      "type": "feed",
      "url": "rsshub://pku/ss/pgadmin"
    }
  ],
  "url": "ss.pku.edu.cn/admission/admbrochure/admission01"
}
```
