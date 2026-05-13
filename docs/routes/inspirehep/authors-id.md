# INSPIRE - Author Search

## Coverage
`index-only`

## Route
- Namespace: `inspirehep`
- Namespace Name: `INSPIRE`
- Route Path: `/authors/:id`
- Route Name: `Author Search`
- Example: `/inspirehep/authors/1696909`
- URL: `inspirehep.net`
- Language: `en`
- Categories: `journal`
- Maintainers: `TonyRL`
- Source Location: `author.ts`
- Source Module: `() => import('@/routes/inspirehep/author.ts')`

## Description
_None_

## Parameters
- `id`: Author ID


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `inspirehep.net/authors/:id`

## Raw JSON
```json
{
  "example": "/inspirehep/authors/1696909",
  "location": "author.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/inspirehep/author.ts')",
  "name": "Author Search",
  "parameters": {
    "id": "Author ID"
  },
  "path": "/authors/:id",
  "radar": [
    {
      "source": [
        "inspirehep.net/authors/:id"
      ]
    }
  ]
}
```
