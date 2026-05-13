# 腾讯网 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `qq`
- Namespace Name: `腾讯网`
- Route Path: `/ac/comic/:id?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `qq.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `None`
- Source Location: `ac/comic.ts`
- Source Module: `() => import('@/routes/qq/ac/comic.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `ac.qq.com/Comic/ComicInfo/id/:id`
  - `ac.qq.com/`
- `target`: `/ac/comic/:id`

## Raw JSON
```json
{
  "location": "ac/comic.ts",
  "maintainers": [],
  "module": "() => import('@/routes/qq/ac/comic.ts')",
  "name": "Unknown",
  "path": "/ac/comic/:id?",
  "radar": [
    {
      "source": [
        "ac.qq.com/Comic/ComicInfo/id/:id",
        "ac.qq.com/"
      ],
      "target": "/ac/comic/:id"
    }
  ]
}
```
