# East China Normal University 华东师范大学 - 公共管理学院通知公告

## Coverage
`index-only`

## Route
- Namespace: `ecnu`
- Namespace Name: `East China Normal University 华东师范大学`
- Route Path: `/ecnu/spm`
- Route Name: `公共管理学院通知公告`
- Example: `/ecnu/spm`
- URL: `www.ecnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `FrozenStarrrr, ChiyoYuki, ECNU-minus`
- Source Location: `spm.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `spm.ecnu.edu.cn`
- `target`: `/spm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ecnu/spm",
  "heat": 0,
  "location": "spm.ts",
  "maintainers": [
    "FrozenStarrrr",
    "ChiyoYuki",
    "ECNU-minus"
  ],
  "name": "公共管理学院通知公告",
  "path": "/spm",
  "radar": [
    {
      "source": [
        "spm.ecnu.edu.cn"
      ],
      "target": "/spm"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(7) ] to not include 'https://mp.weixin.qq.com/s/HJydDDZaMv…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
