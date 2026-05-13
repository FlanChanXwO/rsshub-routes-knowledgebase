# 深圳市罗湖区人民政府 - 沟通交流

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `深圳市罗湖区人民政府`
- Route Path: `/gov/pbc/goutongjiaoliu`
- Route Name: `沟通交流`
- Example: `/gov/pbc/goutongjiaoliu`
- URL: `pbc.gov.cn/goutongjiaoliu/113456/113469/index.html`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `pbc/goutongjiaoliu.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `pbc.gov.cn/goutongjiaoliu/113456/113469/index.html`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/gov/pbc/goutongjiaoliu",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "pbc/goutongjiaoliu.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "沟通交流",
  "parameters": {},
  "path": "/pbc/goutongjiaoliu",
  "radar": [
    {
      "source": [
        "pbc.gov.cn/goutongjiaoliu/113456/113469/index.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国人民银行 - 沟通交流 - Powered by RSSHub",
      "errorAt": "2026-01-06T11:19:10.515Z",
      "errorMessage": "page.goto: Target page, context or browser has been closed\nCall log:\n  - navigating to \"http://www.pbc.gov.cn/goutongjiaoliu/113456/113469/index.html\", waiting until \"domcontentloaded\"\n\n",
      "id": "146226947009457153",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.pbc.gov.cn/goutongjiaoliu/113456/113469/index.html",
      "title": "中国人民银行 - 沟通交流",
      "type": "feed",
      "url": "rsshub://gov/pbc/goutongjiaoliu"
    }
  ],
  "url": "pbc.gov.cn/goutongjiaoliu/113456/113469/index.html"
}
```
