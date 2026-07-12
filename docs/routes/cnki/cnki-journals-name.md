# 中国知网 - 期刊

## Coverage
`index-only`

## Route
- Namespace: `cnki`
- Namespace Name: `中国知网`
- Route Path: `/cnki/journals/:name`
- Route Name: `期刊`
- Example: `/cnki/journals/LKGP`
- URL: `navi.cnki.net`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `Fatpandac, Derekmini, pseudoyu`
- Source Location: `journals.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 期刊缩写，可以在网址中得到


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
  - `navi.cnki.net/knavi/journals/:name/detail`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/cnki/journals/LKGP",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 68,
  "location": "journals.ts",
  "maintainers": [
    "Fatpandac",
    "Derekmini",
    "pseudoyu"
  ],
  "name": "期刊",
  "parameters": {
    "name": "期刊缩写，可以在网址中得到"
  },
  "path": "/journals/:name",
  "radar": [
    {
      "source": [
        "navi.cnki.net/knavi/journals/:name/detail"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "微纳电子技术 - Powered by RSSHub",
      "errorAt": "2026-07-08T05:55:18.033Z",
      "errorMessage": "[GET] \"https://rss.cnki.net/kns/rss.aspx?Journal=BDTQ&Virtual=knavi\": <no response> fetch failed\n",
      "id": "159265390001661952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://navi.cnki.net/knavi/journals/BDTQ/detail?uniplatform=NZKPT",
      "title": "微纳电子技术-CNKI",
      "type": "feed",
      "url": "rsshub://cnki/journals/BDTQ"
    },
    {
      "description": "电子与封装 - Powered by RSSHub",
      "errorAt": "2026-06-24T06:21:45.990Z",
      "errorMessage": "[GET] \"https://rss.cnki.net/kns/rss.aspx?Journal=DYFZ&Virtual=knavi\": <no response> fetch failed\n",
      "id": "159266714924499968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://navi.cnki.net/knavi/journals/DYFZ/detail?uniplatform=NZKPT",
      "title": "电子与封装-CNKI",
      "type": "feed",
      "url": "rsshub://cnki/journals/DYFZ"
    }
  ]
}
```
