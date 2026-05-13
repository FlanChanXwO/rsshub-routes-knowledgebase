# Academia - interest

## Coverage
`index-only`

## Route
- Namespace: `academia`
- Namespace Name: `Academia`
- Route Path: `/topic/:interest`
- Route Name: `interest`
- Example: `/academia/topic/Urban_History`
- URL: `academia.edu`
- Language: `en`
- Categories: `journal`
- Maintainers: `K33k0, cscnk52`
- Source Location: `topics.ts`
- Source Module: `() => import('@/routes/academia/topics.ts')`

## Description
_None_

## Parameters
- `interest`: interest


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `academia.edu/Documents/in/:interest`
- `target`: `/topic/:interest`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/academia/topic/Urban_History",
  "location": "topics.ts",
  "maintainers": [
    "K33k0",
    "cscnk52"
  ],
  "module": "() => import('@/routes/academia/topics.ts')",
  "name": "interest",
  "parameters": {
    "interest": "interest"
  },
  "path": "/topic/:interest",
  "radar": [
    {
      "source": [
        "academia.edu/Documents/in/:interest"
      ],
      "target": "/topic/:interest"
    }
  ],
  "url": "academia.edu"
}
```
