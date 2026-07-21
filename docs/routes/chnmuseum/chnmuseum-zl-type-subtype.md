# National Museum Of China - Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `chnmuseum`
- Namespace Name: `National Museum Of China`
- Route Path: `/chnmuseum/zl/:type?/:subType?`
- Route Name: `Exhibitions`
- Example: `/chnmuseum/zl/lszl/zdzt`
- URL: `www.chnmuseum.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `zl.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: zhanlanyugao（正在展出）、jbcl（基本陈列）、ztcl（专题展览）、lszl（临时展览）、gjzl（国家展览）、gbxz（国博巡展）. Default: All exhibitions.
- `subType`: subtype only works under type lszl（临时展览）, supported values: zdzt（重大主题）、lswh（历史文化）、yscx（艺术创新）、gjjl（国际交流）


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.chnmuseum.cn/zl/`
- `target`: `/zl`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/chnmuseum/zl/lszl/zdzt",
  "heat": 0,
  "location": "zl.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Exhibitions",
  "parameters": {
    "subType": "subtype only works under type lszl（临时展览）, supported values: zdzt（重大主题）、lswh（历史文化）、yscx（艺术创新）、gjjl（国际交流）",
    "type": "Exhibition type, supported values: zhanlanyugao（正在展出）、jbcl（基本陈列）、ztcl（专题展览）、lszl（临时展览）、gjzl（国家展览）、gbxz（国博巡展）. Default: All exhibitions."
  },
  "path": "/zl/:type?/:subType?",
  "radar": [
    {
      "source": [
        "www.chnmuseum.cn/zl/"
      ],
      "target": "/zl"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": []
}
```
