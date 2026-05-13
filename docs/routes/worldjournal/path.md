# 世界新聞網 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `worldjournal`
- Namespace Name: `世界新聞網`
- Route Path: `/:path{.+}?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `worldjournal.com/wj/*path`
- Language: `zh-TW`
- Categories: `None`
- Maintainers: `None`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/worldjournal/index.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `worldjournal.com/wj/*path`
- `target`: `/:path`

## Raw JSON
```json
{
  "location": "index.ts",
  "maintainers": [],
  "module": "() => import('@/routes/worldjournal/index.ts')",
  "name": "Unknown",
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "worldjournal.com/wj/*path"
      ],
      "target": "/:path"
    }
  ],
  "url": "worldjournal.com/wj/*path"
}
```
