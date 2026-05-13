# 虎扑 - 队伍新闻

## Coverage
`index-only`

## Route
- Namespace: `hupu`
- Namespace Name: `虎扑`
- Route Path: `/news/:team`
- Route Name: `队伍新闻`
- Example: `/news/Spurs`
- URL: `m.hupu.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `hyoban`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/hupu/news.ts')`

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
  "location": "news.ts",
  "maintainers": [
    "hyoban"
  ],
  "module": "() => import('@/routes/hupu/news.ts')",
  "name": "队伍新闻",
  "parameters": {
    "team": {
      "description": "全小写的英文队名，例如：spurs, lakers, warriors 等等"
    }
  },
  "path": [
    "/news/:team"
  ],
  "url": "m.hupu.com"
}
```
