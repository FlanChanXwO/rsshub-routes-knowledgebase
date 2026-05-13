# Proceedings of The National Academy of Sciences - Unknown

## Coverage
`index-only`

## Route
- Namespace: `pnas`
- Namespace Name: `Proceedings of The National Academy of Sciences`
- Route Path: `/:topicPath{.+}?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `pnas.org/*topicPath`
- Language: `en`
- Categories: `None`
- Maintainers: `None`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/pnas/index.tsx')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `pnas.org/*topicPath`
- `target`: `/:topicPath`

## Raw JSON
```json
{
  "location": "index.tsx",
  "maintainers": [],
  "module": "() => import('@/routes/pnas/index.tsx')",
  "name": "Unknown",
  "path": "/:topicPath{.+}?",
  "radar": [
    {
      "source": [
        "pnas.org/*topicPath"
      ],
      "target": "/:topicPath"
    }
  ],
  "url": "pnas.org/*topicPath"
}
```
