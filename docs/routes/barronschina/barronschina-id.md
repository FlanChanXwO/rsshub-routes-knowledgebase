# 巴伦周刊中文版 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `barronschina`
- Namespace Name: `巴伦周刊中文版`
- Route Path: `/barronschina/:id?`
- Route Name: `栏目`
- Example: `/barronschina`
- URL: `barronschina.com.cn/`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
栏目 id 留空则返回快讯，在对应页地址栏 `columnId=` 后可以看到。
:::

## Parameters
- `id`: 栏目 id，默认为快讯


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
  - `barronschina.com.cn/`
- `target`: `/:category?`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n栏目 id 留空则返回快讯，在对应页地址栏 `columnId=` 后可以看到。\n:::",
  "example": "/barronschina",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 35,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "id": "栏目 id，默认为快讯"
  },
  "path": "/:id?",
  "radar": [
    {
      "source": [
        "barronschina.com.cn/"
      ],
      "target": "/:category?"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "《巴伦周刊》中文版-快讯 - Powered by RSSHub",
      "errorAt": "2024-10-14T17:38:39.161Z",
      "errorMessage": "[GET] \"http://www.barronschina.com.cn/index/shortNews\": <no response> fetch failed (getaddrinfo ENOTFOUND www.barronschina.com.cn)\n",
      "id": "59951258674929664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.barronschina.com.cn/index/shortNews",
      "title": "《巴伦周刊》中文版-快讯",
      "type": "feed",
      "url": "rsshub://barronschina"
    }
  ],
  "url": "barronschina.com.cn/"
}
```
