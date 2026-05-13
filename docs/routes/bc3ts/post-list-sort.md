# 爆料公社 - 動態

## Coverage
`index-only`

## Route
- Namespace: `bc3ts`
- Namespace Name: `爆料公社`
- Route Path: `/post/list/:sort?`
- Route Name: `動態`
- Example: `/bc3ts/post/list`
- URL: `web.bc3ts.net`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `list.tsx`
- Source Module: `() => import('@/routes/bc3ts/list.tsx')`

## Description
_None_

## Parameters
- `sort`: 排序方式，`1` 為最新，`2` 為熱門，默认為 `1`


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `web.bc3ts.net`

## Raw JSON
```json
{
  "example": "/bc3ts/post/list",
  "features": {
    "antiCrawler": true
  },
  "location": "list.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/bc3ts/list.tsx')",
  "name": "動態",
  "parameters": {
    "sort": "排序方式，`1` 為最新，`2` 為熱門，默认為 `1`"
  },
  "path": "/post/list/:sort?",
  "radar": [
    {
      "source": [
        "web.bc3ts.net"
      ]
    }
  ]
}
```
