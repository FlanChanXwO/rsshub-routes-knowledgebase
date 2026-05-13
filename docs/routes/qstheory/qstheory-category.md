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
  "heat": 58,
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
    "message": "AssertionError: expected [ …(33) ] to not include 'https://www.qstheory.cn/20260414/8005…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
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
      "description": "党建 - 求是网 - Powered by RSSHub",
      "errorAt": "2024-12-10T05:21:10.650Z",
      "errorMessage": "[GET] \"../20260510/25691e161de540a7bb95bf6b73c8cbf2/c.html\": <no response> Failed to parse URL from ../20260510/25691e161de540a7bb95bf6b73c8cbf2/c.html\n",
      "id": "83847865922732032",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.qstheory.cn/cpc/index.htm",
      "title": "党建 - 求是网",
      "type": "feed",
      "url": "rsshub://qstheory/cpc"
    }
  ]
}
```
