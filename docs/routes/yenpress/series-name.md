# Yen Press - Series

## Coverage
`index-only`

## Route
- Namespace: `yenpress`
- Namespace Name: `Yen Press`
- Route Path: `/series/:name`
- Route Name: `Series`
- Example: `/yenpress/series/alya-sometimes-hides-her-feelings-in-russian`
- URL: `yenpress.com`
- Language: `en`
- Categories: `reading`
- Maintainers: `TonyRL`
- Source Location: `series.tsx`
- Source Module: `() => import('@/routes/yenpress/series.tsx')`

## Description
_None_

## Parameters
- `name`: Series name


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `yenpress.com/series/:name`
- `target`: `/series/:name`

## Raw JSON
```json
{
  "example": "/yenpress/series/alya-sometimes-hides-her-feelings-in-russian",
  "location": "series.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/yenpress/series.tsx')",
  "name": "Series",
  "parameters": {
    "name": "Series name"
  },
  "path": "/series/:name",
  "radar": [
    {
      "source": [
        "yenpress.com/series/:name"
      ],
      "target": "/series/:name"
    }
  ]
}
```
