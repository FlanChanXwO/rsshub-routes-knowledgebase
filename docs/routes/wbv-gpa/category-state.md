# WBV-GPA - Angebote

## Coverage
`index-only`

## Route
- Namespace: `wbv-gpa`
- Namespace Name: `WBV-GPA`
- Route Path: `/:category?/:state?`
- Route Name: `Angebote`
- Example: `/wbv-gpa/wohnungen/wien`
- URL: `wbv-gpa.at`
- Language: `de`
- Categories: `other`
- Maintainers: `sk22`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/wbv-gpa/index.ts')`

## Description
Search housing by WBV-GPA, see "Angebote" menu item in https://www.wbv-gpa.at.
Filtering by state is done client-side.

## Parameters
- `category`: Anything behind `/angebote/` in the URL. Default: `wohnungen`
- `state`: Optionally filter by Austrian state (`wien`, `steiermark`, ...)


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `https://www.wbv-gpa.at/wohnungen/`
  - `https://www.wbv-gpa.at/angebote//:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "\nSearch housing by WBV-GPA, see \"Angebote\" menu item in https://www.wbv-gpa.at.\nFiltering by state is done client-side.\n",
  "example": "/wbv-gpa/wohnungen/wien",
  "location": "index.ts",
  "maintainers": [
    "sk22"
  ],
  "module": "() => import('@/routes/wbv-gpa/index.ts')",
  "name": "Angebote",
  "parameters": {
    "category": "Anything behind `/angebote/` in the URL. Default: `wohnungen`",
    "state": "Optionally filter by Austrian state (`wien`, `steiermark`, ...)"
  },
  "path": "/:category?/:state?",
  "radar": [
    {
      "source": [
        "https://www.wbv-gpa.at/wohnungen/",
        "https://www.wbv-gpa.at/angebote//:category"
      ],
      "target": "/:category"
    }
  ]
}
```
