# 深圳市罗湖区人民政府 - 宁波市国资委-公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `深圳市罗湖区人民政府`
- Route Path: `/gov/zj/ningbogzw-notice/:colId?`
- Route Name: `宁波市国资委-公告`
- Example: `/gov/zj/ningbogzw-notice/1229116730`
- URL: `gzw.ningbo.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `zj/ningbogzw-notice.ts`
- Source Module: `_None_`

## Description
| 公告类别                           | colId      |
| ---------------------------------- | ---------- |
| 首页 - 市属国企招聘信息 - 招聘公告 | 1229116730 |

## Parameters
- `colId`: 公告分类id、详细信息点击源网站http://gzw.ningbo.gov.cn/请求中寻找


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `gzw.ningbo.gov.cn/col/col1229116730/index.html`
- `target`: `/zj/ningbogzw-notice/:colId?`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 公告类别                           | colId      |\n| ---------------------------------- | ---------- |\n| 首页 - 市属国企招聘信息 - 招聘公告 | 1229116730 |",
  "example": "/gov/zj/ningbogzw-notice/1229116730",
  "heat": 2,
  "location": "zj/ningbogzw-notice.ts",
  "maintainers": [
    "HaoyuLee"
  ],
  "name": "宁波市国资委-公告",
  "parameters": {
    "colId": "公告分类id、详细信息点击源网站http://gzw.ningbo.gov.cn/请求中寻找"
  },
  "path": "/zj/ningbogzw-notice/:colId?",
  "radar": [
    {
      "source": [
        "gzw.ningbo.gov.cn/col/col1229116730/index.html"
      ],
      "target": "/zj/ningbogzw-notice/:colId?"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "宁波市国资委 - Powered by RSSHub",
      "errorAt": "2025-10-11T09:02:36.785Z",
      "errorMessage": "Cannot read properties of null (reading 'map')\n",
      "id": "140564077109703680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://gzw.ningbo.gov.cn/col/col1229116730/index.html",
      "title": "宁波市国资委",
      "type": "feed",
      "url": "rsshub://gov/zj/ningbogzw-notice"
    }
  ],
  "url": "gzw.ningbo.gov.cn"
}
```
