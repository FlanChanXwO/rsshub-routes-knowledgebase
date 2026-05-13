# 浙江大学 - 普通栏目 如学术 / 图片 / 新闻等

## Coverage
`index-only`

## Route
- Namespace: `zju`
- Namespace Name: `浙江大学`
- Route Path: `/zju/list/:type`
- Route Name: `普通栏目 如学术 / 图片 / 新闻等`
- Example: `/zju/list/xs`
- URL: `physics.zju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Jeason0228`
- Source Location: `list.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: `xs`为学术，`xw`为新闻，`5461`是图片新闻，`578`是浙大报道，具体参数参考左侧的菜单


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/zju/list/xs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "list.ts",
  "maintainers": [
    "Jeason0228"
  ],
  "name": "普通栏目 如学术 / 图片 / 新闻等",
  "parameters": {
    "type": "`xs`为学术，`xw`为新闻，`5461`是图片新闻，`578`是浙大报道，具体参数参考左侧的菜单"
  },
  "path": "/list/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
