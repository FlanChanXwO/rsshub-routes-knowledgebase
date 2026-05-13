# National Bureau of Economic Research - New Papers

## Coverage
`index-only`

## Route
- Namespace: `nber`
- Namespace Name: `National Bureau of Economic Research`
- Route Path: `/new`
- Route Name: `New Papers`
- Example: `/nber/new`
- URL: `nber.org/papers`
- Language: `en`
- Categories: `journal`
- Maintainers: `5upernova-heng`
- Source Location: `new.ts`
- Source Module: `() => import('@/routes/nber/new.ts')`

## Description
Papers that are published in this week.

## Parameters
_None_


## Features
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `nber.org/papers`

## Raw JSON
```json
{
  "description": "Papers that are published in this week.",
  "example": "/nber/new",
  "features": {
    "supportScihub": true
  },
  "location": "new.ts",
  "maintainers": [
    "5upernova-heng"
  ],
  "module": "() => import('@/routes/nber/new.ts')",
  "name": "New Papers",
  "path": "/new",
  "radar": [
    {
      "source": [
        "nber.org/papers"
      ]
    }
  ],
  "url": "nber.org/papers"
}
```
