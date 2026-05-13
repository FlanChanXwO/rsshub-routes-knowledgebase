# 虎扑 - 队伍新闻

## Coverage
`index-only`

## Route
- Namespace: `hupu`
- Namespace Name: `虎扑`
- Route Path: `/hupu/news/:team`
- Route Name: `队伍新闻`
- Example: `/news/Spurs`
- URL: `m.hupu.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `hyoban`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `team`: {"description": "全小写的英文队名，例如：spurs, lakers, warriors 等等"}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/news/Spurs",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "hyoban"
  ],
  "name": "队伍新闻",
  "parameters": {
    "team": {
      "description": "全小写的英文队名，例如：spurs, lakers, warriors 等等"
    }
  },
  "path": [
    "/news/:team"
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 404 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "m.hupu.com"
}
```
