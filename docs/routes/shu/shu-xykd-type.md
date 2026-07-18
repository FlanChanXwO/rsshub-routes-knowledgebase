# 上海大学 - 校园看点

## Coverage
`index-only`

## Route
- Namespace: `shu`
- Namespace Name: `上海大学`
- Route Path: `/shu/xykd/:type?`
- Route Name: `校园看点`
- Example: `/shu/xykd/xsbg`
- URL: `www.shu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `GhhG123`
- Source Location: `xykd.ts`
- Source Module: `_None_`

## Description
| 文化信息 | 学术报告 |
| -------- | -------- |
| whxx     | xsbg     |

## Parameters
- `type`: 分类，默认为学术公告


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
  - `www.shu.edu.cn/`
- `target`: `/xykd`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 文化信息 | 学术报告 |\n| -------- | -------- |\n| whxx     | xsbg     |",
  "example": "/shu/xykd/xsbg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "xykd.ts",
  "maintainers": [
    "GhhG123"
  ],
  "name": "校园看点",
  "parameters": {
    "type": "分类，默认为学术公告"
  },
  "path": "/xykd/:type?",
  "radar": [
    {
      "source": [
        "www.shu.edu.cn/"
      ],
      "target": "/xykd"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "上海大学 - 文化信息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84819966471031808",
      "image": "https://www.shu.edu.cn/__local/0/08/C6/1EABE492B0CF228A5564D6E6ABE_779D1EE3_5BF7.png",
      "ownerUserId": null,
      "siteUrl": "https://www.shu.edu.cn/xnrc/whxx.htm",
      "title": "上海大学 - 文化信息",
      "type": "feed",
      "url": "rsshub://shu/xykd/whxx"
    },
    {
      "description": "上海大学 - 学术报告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84658986070627328",
      "image": "https://www.shu.edu.cn/__local/0/08/C6/1EABE492B0CF228A5564D6E6ABE_779D1EE3_5BF7.png",
      "ownerUserId": null,
      "siteUrl": "https://www.shu.edu.cn/xnrc/xsbg.htm",
      "title": "上海大学 - 学术报告",
      "type": "feed",
      "url": "rsshub://shu/xykd/xsbg"
    }
  ],
  "url": "www.shu.edu.cn/"
}
```
