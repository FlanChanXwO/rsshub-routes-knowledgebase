# 观察者网 - 观学院

## Coverage
`index-only`

## Route
- Namespace: `guancha`
- Namespace Name: `观察者网`
- Route Path: `/guancha/member/:category?`
- Route Name: `观学院`
- Example: `/guancha/member/recommend`
- URL: `guancha.cn/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `member.ts`
- Source Module: `_None_`

## Description
| 精选      | 观书堂 | 在线课  | 观学院   |
| --------- | ------ | ------- | -------- |
| recommend | books  | courses | huodongs |

## Parameters
- `category`: 分类，见下表


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
  - `guancha.cn/`
- `target`: `/:category?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 精选      | 观书堂 | 在线课  | 观学院   |\n| --------- | ------ | ------- | -------- |\n| recommend | books  | courses | huodongs |",
  "example": "/guancha/member/recommend",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "member.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "观学院",
  "parameters": {
    "category": "分类，见下表"
  },
  "path": "/member/:category?",
  "radar": [
    {
      "source": [
        "guancha.cn/"
      ],
      "target": "/:category?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "观学院 - 精选 - Powered by RSSHub",
      "errorAt": "2026-07-15T05:00:01.153Z",
      "errorMessage": "Failed to fetch\n",
      "id": "83419287598017536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://member.guancha.cn/index.html",
      "title": "观学院 - 精选",
      "type": "feed",
      "url": "rsshub://guancha/member/recommend"
    },
    {
      "description": "观学院 - 精选 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "153011740197426176",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://member.guancha.cn/index.html",
      "title": "观学院 - 精选",
      "type": "feed",
      "url": "rsshub://guancha/member"
    }
  ],
  "url": "guancha.cn/"
}
```
