# U9A9 - Search

## Coverage
`index-only`

## Route
- Namespace: `u9a9`
- Namespace Name: `U9A9`
- Route Path: `/search/:keyword/:preview?`
- Route Name: `Search`
- Example: `/u9a9/search/新片速递`
- URL: `u9a9.com/`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/u9a9/index.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `u9a9.com/`
- `target`: ``

## Raw JSON
```json
{
  "example": "/u9a9/search/新片速递",
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/u9a9/index.ts')",
  "name": "Search",
  "path": [
    "/:preview?",
    "/search/:keyword/:preview?"
  ],
  "radar": [
    {
      "source": [
        "u9a9.com/"
      ],
      "target": ""
    }
  ],
  "url": "u9a9.com/"
}
```
