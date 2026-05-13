# 意林杂志 - 近期文章汇总

## Coverage
`index-only`

## Route
- Namespace: `yilinzazhi`
- Namespace Name: `意林杂志`
- Route Path: `/yilinzazhi/latest`
- Route Name: `近期文章汇总`
- Example: `/yilinzazhi/latest`
- URL: `www.yilinzazhi.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `g0ngjie`
- Source Location: `latest.ts`
- Source Module: `_None_`

## Description
最近一期的文章汇总

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.yilinzazhi.com`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "最近一期的文章汇总",
  "example": "/yilinzazhi/latest",
  "heat": 511,
  "location": "latest.ts",
  "maintainers": [
    "g0ngjie"
  ],
  "name": "近期文章汇总",
  "path": "/latest",
  "radar": [
    {
      "source": [
        "www.yilinzazhi.com"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "意林 - 近期文章汇总 - Powered by RSSHub",
      "errorAt": "2024-10-08T03:58:34.168Z",
      "errorMessage": "Cannot read properties of undefined (reading 'link')\nCannot read properties of undefined (reading 'link')\nCannot read properties of undefined (reading 'link')\nCannot read properties of undefined (reading 'link')\n",
      "id": "60546375521699840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yilinzazhi.com/2024/yl20248/index.html",
      "title": "意林 - 近期文章汇总",
      "type": "feed",
      "url": "rsshub://yilinzazhi/latest"
    }
  ],
  "url": "www.yilinzazhi.com",
  "view": 0
}
```
