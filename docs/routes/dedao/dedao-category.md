# 得到 - 文章

## Coverage
`index-only`

## Route
- Namespace: `dedao`
- Namespace Name: `得到`
- Route Path: `/dedao/:category?`
- Route Name: `文章`
- Example: `/dedao`
- URL: `dedao.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 新闻 | 人物故事 | 视频  |
| ---- | -------- | ----- |
| news | figure   | video |

## Parameters
- `category`: 分类，见下表，默认为`news`


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 新闻 | 人物故事 | 视频  |\n| ---- | -------- | ----- |\n| news | figure   | video |",
  "example": "/dedao",
  "heat": 615,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "文章",
  "parameters": {
    "category": "分类，见下表，默认为`news`"
  },
  "path": "/:category?",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "得到App、得到高研院、知识春晚、How Talk、罗振宇“时间的朋友”跨年演讲的最新动态，以及刘润、梁宁、吴军、香帅、薛兆丰等得到系老师的人物故事。2020年除夕夜,知识春晚登陆深圳卫视。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84134389101132800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.igetget.com/news",
      "title": "得到大事件 - 新闻",
      "type": "feed",
      "url": "rsshub://dedao"
    },
    {
      "description": "得到App、得到高研院、知识春晚、How Talk、罗振宇“时间的朋友”跨年演讲的最新动态，以及刘润、梁宁、吴军、香帅、薛兆丰等得到系老师的人物故事。2020年除夕夜,知识春晚登陆深圳卫视。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54179880911627267",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.igetget.com/news",
      "title": "得到大事件 - 新闻",
      "type": "feed",
      "url": "rsshub://dedao/news"
    }
  ]
}
```
