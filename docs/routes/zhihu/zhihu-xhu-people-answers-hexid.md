# 知乎 - xhu - 用户回答

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/xhu/people/answers/:hexId`
- Route Name: `xhu - 用户回答`
- Example: `/zhihu/xhu/people/answers/246e6cf44e94cefbf4b959cb5042bc91`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/answers.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `hexId`: 用户的 16 进制 id，获取方式同 [xhu - 用户动态](#zhi-hu-xhu-yong-hu-dong-tai)


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
  - `www.zhihu.com/people/:id/answers`
- `target`: `/people/answers/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/xhu/people/answers/246e6cf44e94cefbf4b959cb5042bc91",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "xhu/answers.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "xhu - 用户回答",
  "parameters": {
    "hexId": "用户的 16 进制 id，获取方式同 [xhu - 用户动态](#zhi-hu-xhu-yong-hu-dong-tai)"
  },
  "path": "/xhu/people/answers/:hexId",
  "radar": [
    {
      "source": [
        "www.zhihu.com/people/:id/answers"
      ],
      "target": "/people/answers/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "于咬敢的知乎回答 - Powered by RSSHub",
      "errorAt": "2025-07-13T11:00:40.415Z",
      "errorMessage": "[GET] \"https://api.zhihuvvv.workers.dev/guests/token\": 401 Unauthorized\n",
      "id": "57319071807974400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/246e6cf44e94cefbf4b959cb5042bc91/answers",
      "title": "于咬敢的知乎回答",
      "type": "feed",
      "url": "rsshub://zhihu/xhu/people/answers/246e6cf44e94cefbf4b959cb5042bc91"
    }
  ]
}
```
