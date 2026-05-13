# INSPIRE - Literature Search

## Coverage
`index-only`

## Route
- Namespace: `inspirehep`
- Namespace Name: `INSPIRE`
- Route Path: `/literature/:q`
- Route Name: `Literature Search`
- Example: `/inspirehep/literature/Physics`
- URL: `inspirehep.net`
- Language: `en`
- Categories: `journal`
- Maintainers: `TonyRL`
- Source Location: `literature.ts`
- Source Module: `() => import('@/routes/inspirehep/literature.ts')`

## Description
_None_

## Parameters
- `q`: Search keyword


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `inspirehep.net/literature`

## Raw JSON
```json
{
  "example": "/inspirehep/literature/Physics",
  "location": "literature.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/inspirehep/literature.ts')",
  "name": "Literature Search",
  "parameters": {
    "q": "Search keyword"
  },
  "path": "/literature/:q",
  "radar": [
    {
      "source": [
        "inspirehep.net/literature"
      ]
    }
  ]
}
```
