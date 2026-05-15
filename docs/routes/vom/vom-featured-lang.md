# Voice of Mongolia - News

## Coverage
`index-only`

## Route
- Namespace: `vom`
- Namespace Name: `Voice of Mongolia`
- Route Path: `/vom/featured/:lang?`
- Route Name: `News`
- Example: `/vom/featured`
- URL: `vom.mn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `featured.ts`
- Source Module: `_None_`

## Description
| English | 日本語 | Монгол | Русский | 简体中文 |
| ------- | ------ | ------ | ------- | -------- |
| en      | ja     | mn     | ru      | zh       |

## Parameters
- `lang`: Language, see the table below, `mn` by default


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
  - `vom.mn/:lang`
  - `vom.mn/`
- `target`: `/featured/:lang`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| English | 日本語 | Монгол | Русский | 简体中文 |\n| ------- | ------ | ------ | ------- | -------- |\n| en      | ja     | mn     | ru      | zh       |",
  "example": "/vom/featured",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "featured.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "News",
  "parameters": {
    "lang": "Language, see the table below, `mn` by default"
  },
  "path": "/featured/:lang?",
  "radar": [
    {
      "source": [
        "vom.mn/:lang",
        "vom.mn/"
      ],
      "target": "/featured/:lang"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ 'http://www.vom.mn/mn/p/55289' ] to not include 'http://www.vom.mn/mn/p/55289'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "VoM.mn - Voice of Mongolia - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "116831194976780288",
      "image": "http://www.vom.mn/dist/images/vom-logo.png",
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "VoM.mn - Voice of Mongolia",
      "type": "feed",
      "url": "rsshub://vom/featured/en"
    },
    {
      "description": "VoM.mn - Voice of Mongolia - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64309319450846208",
      "image": "http://www.vom.mn/dist/images/vom-logo.png",
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "VoM.mn - Voice of Mongolia",
      "type": "feed",
      "url": "rsshub://vom/featured"
    }
  ]
}
```
