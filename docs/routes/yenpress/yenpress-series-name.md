# Yen Press - Series

## Coverage
`index-only`

## Route
- Namespace: `yenpress`
- Namespace Name: `Yen Press`
- Route Path: `/yenpress/series/:name`
- Route Name: `Series`
- Example: `/yenpress/series/alya-sometimes-hides-her-feelings-in-russian`
- URL: `yenpress.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `TonyRL`
- Source Location: `series.tsx`
- Source Module: `_None_`

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
  "categories": [
    "reading"
  ],
  "example": "/yenpress/series/alya-sometimes-hides-her-feelings-in-russian",
  "heat": 0,
  "location": "series.tsx",
  "maintainers": [
    "TonyRL"
  ],
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
  ],
  "topFeeds": []
}
```
