# ELSEVIER - Unknown

## Coverage
`index-only`

## Route
- Namespace: `elsevier`
- Namespace Name: `ELSEVIER`
- Route Path: `/:journal/latest`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `www.sciencedirect.com`
- Language: `en`
- Categories: `None`
- Maintainers: `None`
- Source Location: `journal.ts`
- Source Module: `() => import('@/routes/elsevier/journal.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sciencedirect.com/journal/:journal/*`
- `target`: `/:journal`

## Raw JSON
```json
{
  "location": "journal.ts",
  "maintainers": [],
  "module": "() => import('@/routes/elsevier/journal.ts')",
  "name": "Unknown",
  "path": [
    "/:journal/latest",
    "/:journal"
  ],
  "radar": [
    {
      "source": [
        "www.sciencedirect.com/journal/:journal/*"
      ],
      "target": "/:journal"
    }
  ]
}
```
