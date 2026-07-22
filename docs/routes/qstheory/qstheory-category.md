# 求是网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `qstheory`
- Namespace Name: `求是网`
- Route Path: `/qstheory/:category?`
- Route Name: `分类`
- Example: `/qstheory`
- URL: `www.qstheory.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 头条    | 网评 | 视频 | 原创   | 经济    | 政治     | 文化    | 社会    | 党建 | 科教    | 生态    | 国防    | 国际          | 图书  | 学习笔记 | 理论文选 |
| ------- | ---- | ---- | ------ | ------- | -------- | ------- | ------- | ---- | ------- | ------- | ------- | ------------- | ----- | -------- | -------- |
| toutiao | qswp | qssp | qslgxd | economy | politics | culture | society | cpc  | science | zoology | defense | international | books | xxbj     | llwx     |

## Parameters
- `industry`: 分类，见下表


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.qstheory.cn/v9zhuanqu/:category/index.htm`
  - `www.qstheory.cn/qszq/:category/index.htm`
  - `www.qstheory.cn/:category/index.htm`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 头条    | 网评 | 视频 | 原创   | 经济    | 政治     | 文化    | 社会    | 党建 | 科教    | 生态    | 国防    | 国际          | 图书  | 学习笔记 | 理论文选 |\n| ------- | ---- | ---- | ------ | ------- | -------- | ------- | ------- | ---- | ------- | ------- | ------- | ------------- | ----- | -------- | -------- |\n| toutiao | qswp | qssp | qslgxd | economy | politics | culture | society | cpc  | science | zoology | defense | international | books | xxbj     | llwx     |",
  "example": "/qstheory",
  "heat": 64,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "industry": "分类，见下表"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.qstheory.cn/v9zhuanqu/:category/index.htm",
        "www.qstheory.cn/qszq/:category/index.htm",
        "www.qstheory.cn/:category/index.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "- 求是网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80832914000440320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.qstheory.cn/v9zhuanqu/toutiao/index.htm",
      "title": "- 求是网",
      "type": "feed",
      "url": "rsshub://qstheory"
    },
    {
      "description": "- 求是网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81625152130833408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.qstheory.cn/v9zhuanqu/toutiao/index.htm",
      "title": "- 求是网",
      "type": "feed",
      "url": "rsshub://qstheory/toutiao"
    }
  ]
}
```
