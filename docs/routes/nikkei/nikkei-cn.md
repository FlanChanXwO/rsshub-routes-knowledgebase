# The Nikkei 日本経済新聞 - 中文版新闻

## Coverage
`index-only`

## Route
- Namespace: `nikkei`
- Namespace Name: `The Nikkei 日本経済新聞`
- Route Path: `/nikkei/cn/*`
- Route Name: `中文版新闻`
- Example: `/nikkei/cn`
- URL: `nikkei.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `cn/index.ts`
- Source Module: `_None_`

## Description
::: tip
如 [中国 经济 日经中文网](https://cn.nikkei.com/china/ceconomy.html) 的 URL 为 `https://cn.nikkei.com/china/ceconomy.html` 对应路由为 [`/nikkei/cn/cn/china/ceconomy`](https://rsshub.app/nikkei/cn/cn/china/ceconomy)

如 [中國 經濟 日經中文網](https://zh.cn.nikkei.com/china/ceconomy.html) 的 URL 为 `https://zh.cn.nikkei.com/china/ceconomy.html` 对应路由为 [`/nikkei/cn/zh/china/ceconomy`](https://rsshub.app/nikkei/cn/zh/china/ceconomy)

特别地，当 `path` 填入 `rss` 后（如路由为 [`/nikkei/cn/cn/rss`](https://rsshub.app/nikkei/cn/cn/rss)），此时返回的是 [官方 RSS 的内容](https://cn.nikkei.com/rss.html)
:::

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `title`: `中文版新闻`
- `source`:
  - `cn.nikkei.com/:category/:type`
  - `cn.nikkei.com/:category`
  - `cn.nikkei.com/`
### Rule 2
- `title`: `中文版新聞`
- `source`:
  - `zh.cn.nikkei.com/:category/:type`
  - `zh.cn.nikkei.com/:category`
  - `zh.cn.nikkei.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\n如 [中国 经济 日经中文网](https://cn.nikkei.com/china/ceconomy.html) 的 URL 为 `https://cn.nikkei.com/china/ceconomy.html` 对应路由为 [`/nikkei/cn/cn/china/ceconomy`](https://rsshub.app/nikkei/cn/cn/china/ceconomy)\n\n如 [中國 經濟 日經中文網](https://zh.cn.nikkei.com/china/ceconomy.html) 的 URL 为 `https://zh.cn.nikkei.com/china/ceconomy.html` 对应路由为 [`/nikkei/cn/zh/china/ceconomy`](https://rsshub.app/nikkei/cn/zh/china/ceconomy)\n\n特别地，当 `path` 填入 `rss` 后（如路由为 [`/nikkei/cn/cn/rss`](https://rsshub.app/nikkei/cn/cn/rss)），此时返回的是 [官方 RSS 的内容](https://cn.nikkei.com/rss.html)\n:::",
  "example": "/nikkei/cn",
  "heat": 354,
  "location": "cn/index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "中文版新闻",
  "path": "/cn/*",
  "radar": [
    {
      "source": [
        "cn.nikkei.com/:category/:type",
        "cn.nikkei.com/:category",
        "cn.nikkei.com/"
      ],
      "title": "中文版新闻"
    },
    {
      "source": [
        "zh.cn.nikkei.com/:category/:type",
        "zh.cn.nikkei.com/:category",
        "zh.cn.nikkei.com/"
      ],
      "title": "中文版新聞"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "日经中文网--日本经济新闻中文版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57030132765825024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.nikkei.com/cn",
      "title": "日经中文网--日本经济新闻中文版",
      "type": "feed",
      "url": "rsshub://nikkei/cn"
    },
    {
      "description": "日经中文网--日本经济新闻中文版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62743886183348224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.nikkei.com/cn/*",
      "title": "日经中文网--日本经济新闻中文版",
      "type": "feed",
      "url": "rsshub://nikkei/cn/*"
    }
  ]
}
```
