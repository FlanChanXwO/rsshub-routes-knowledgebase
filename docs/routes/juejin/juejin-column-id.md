# 掘金 - 专栏

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/juejin/column/:id`
- Route Name: `专栏`
- Example: `/juejin/column/6960559453037199391`
- URL: `juejin.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `xiangzy1`
- Source Location: `column.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 专栏 id, 可在专栏页 URL 中找到


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
  - `juejin.cn/column/:id`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/juejin/column/6960559453037199391",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 250,
  "location": "column.ts",
  "maintainers": [
    "xiangzy1"
  ],
  "name": "专栏",
  "parameters": {
    "id": "专栏 id, 可在专栏页 URL 中找到"
  },
  "path": "/column/:id",
  "radar": [
    {
      "source": [
        "juejin.cn/column/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Kotlin 技术月报 - 程序员江同学的专栏 - 掘金 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74651187522499584",
      "image": "https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/e02bf6fdddb14548ae91e6fd7f220c7b~tplv-k3u1fbpfcp-watermark.image?",
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/column/7251113487316353081",
      "title": "Kotlin 技术月报 - 程序员江同学的专栏 - 掘金",
      "type": "feed",
      "url": "rsshub://juejin/column/7251113487316353081"
    },
    {
      "description": "鸿蒙应用开发从入门到入行 - 猫林老师的专栏 - 掘金 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74378857053297664",
      "image": "https://p26-juejin-sign.byteimg.com/tos-cn-i-k3u1fbpfcp/1629d2c35b5e4e4981f2ba0aa2acf111~tplv-k3u1fbpfcp-jj-mark-v1:0:0:0:0:5o6Y6YeR5oqA5pyv56S-5Yy6IEAg54yr5p6X6ICB5biI:q75.awebp?rk3s=f64ab15b&x-expires=1779155798&x-signature=m39ihXx3g4ehYUfeyQbtCdVXzxE%3D",
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/column/7397592619810111507",
      "title": "鸿蒙应用开发从入门到入行 - 猫林老师的专栏 - 掘金",
      "type": "feed",
      "url": "rsshub://juejin/column/7397592619810111507"
    }
  ]
}
```
