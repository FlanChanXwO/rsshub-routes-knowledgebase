# 懂球帝 - 早报

## Coverage
`index-only`

## Route
- Namespace: `dongqiudi`
- Namespace Name: `懂球帝`
- Route Path: `/dongqiudi/daily`
- Route Name: `早报`
- Example: `/dongqiudi/daily`
- URL: `www.dongqiudi.com/special/48`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `HenryQW`
- Source Location: `daily.ts`
- Source Module: `_None_`

## Description
::: tip
部分球队和球员可能会有两个 id, 正确 id 应该由 `5000` 开头.
:::

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dongqiudi.com/special/48`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "description": "::: tip\n部分球队和球员可能会有两个 id, 正确 id 应该由 `5000` 开头.\n:::",
  "example": "/dongqiudi/daily",
  "heat": 0,
  "location": "daily.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "早报",
  "path": "/daily",
  "radar": [
    {
      "source": [
        "www.dongqiudi.com/special/48"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 301 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.dongqiudi.com/special/48"
}
```
