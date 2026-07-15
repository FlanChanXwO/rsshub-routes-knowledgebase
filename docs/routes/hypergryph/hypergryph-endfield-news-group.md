# 鹰角网络 - 明日方舟：终末地 - 游戏公告与新闻

## Coverage
`index-only`

## Route
- Namespace: `hypergryph`
- Namespace Name: `鹰角网络`
- Route Path: `/hypergryph/endfield/news/:group?`
- Route Name: `明日方舟：终末地 - 游戏公告与新闻`
- Example: `/hypergryph/endfield/news`
- URL: `endfield.hypergryph.com/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `E-larex`
- Source Location: `endfield/news.ts`
- Source Module: `_None_`

## Description
| 全部 | 公告    | 活动   | 新闻 |
| ---- | ------- | ------ | ---- |
| ALL  | notices | events | news |

## Parameters
- `group`: 分组，默认为 `ALL`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `endfield.hypergryph.com/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 全部 | 公告    | 活动   | 新闻 |\n| ---- | ------- | ------ | ---- |\n| ALL  | notices | events | news |",
  "example": "/hypergryph/endfield/news",
  "heat": 0,
  "location": "endfield/news.ts",
  "maintainers": [
    "E-larex"
  ],
  "name": "明日方舟：终末地 - 游戏公告与新闻",
  "parameters": {
    "group": "分组，默认为 `ALL`"
  },
  "path": "/endfield/news/:group?",
  "radar": [
    {
      "source": [
        "endfield.hypergryph.com/news"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processImmediate (node:internal/timers:472:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "endfield.hypergryph.com/news"
}
```
