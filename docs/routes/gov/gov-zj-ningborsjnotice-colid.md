# 深圳市罗湖区人民政府 - 宁波市人力资源和社会保障局-公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `深圳市罗湖区人民政府`
- Route Path: `/gov/zj/ningborsjnotice/:colId?`
- Route Name: `宁波市人力资源和社会保障局-公告`
- Example: `/gov/zj/ningborsjnotice/1229676740`
- URL: `rsj.ningbo.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `zj/ningborsjnotice.ts`
- Source Module: `_None_`

## Description
| 公告类别         | colId      |
| ---------------- | ---------- |
| 事业单位进人公告 | 1229676740 |

## Parameters
- `colId`: 公告分类id、详细信息点击源网站http://rsj.ningbo.gov.cn/请求中寻找


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `rsj.ningbo.gov.cn/col/col1229676740/index.html`
- `target`: `/zj/ningborsjnotice/:colId?`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 公告类别         | colId      |\n| ---------------- | ---------- |\n| 事业单位进人公告 | 1229676740 |",
  "example": "/gov/zj/ningborsjnotice/1229676740",
  "heat": 0,
  "location": "zj/ningborsjnotice.ts",
  "maintainers": [
    "HaoyuLee"
  ],
  "name": "宁波市人力资源和社会保障局-公告",
  "parameters": {
    "colId": "公告分类id、详细信息点击源网站http://rsj.ningbo.gov.cn/请求中寻找"
  },
  "path": "/zj/ningborsjnotice/:colId?",
  "radar": [
    {
      "source": [
        "rsj.ningbo.gov.cn/col/col1229676740/index.html"
      ],
      "target": "/zj/ningborsjnotice/:colId?"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [],
  "url": "rsj.ningbo.gov.cn"
}
```
