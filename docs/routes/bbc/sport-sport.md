# BBC - Sport

## Coverage
`index-only`

## Route
- Namespace: `bbc`
- Namespace Name: `BBC`
- Route Path: `/sport/:sport`
- Route Name: `Sport`
- Example: `/bbc/sport/formula1`
- URL: `bbc.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `sport.ts`
- Source Module: `() => import('@/routes/bbc/sport.ts')`

## Description
_None_

## Parameters
- `sport`: The sport to fetch news for, can be found in the URL.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bbc.com/sport/:sport`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/bbc/sport/formula1",
  "location": "sport.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/bbc/sport.ts')",
  "name": "Sport",
  "parameters": {
    "sport": "The sport to fetch news for, can be found in the URL."
  },
  "path": "/sport/:sport",
  "radar": [
    {
      "source": [
        "www.bbc.com/sport/:sport"
      ]
    }
  ]
}
```
