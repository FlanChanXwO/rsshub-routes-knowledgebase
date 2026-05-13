# Steam - Store Search

## Coverage
`index-only`

## Route
- Namespace: `steam`
- Namespace Name: `Steam`
- Route Path: `/search/:params`
- Route Name: `Store Search`
- Example: `/steam/search/sort_by=Released_DESC&tags=492&category1=10&os=linux`
- URL: `store.steampowered.com`
- Language: `en`
- Categories: `game`
- Maintainers: `moppman`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/steam/search.ts')`

## Description
_None_

## Parameters
- `params`: Query parameters for a Steam Store search.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `store.steampowered.com`
  - `store.steampowered.com/search/:params`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/steam/search/sort_by=Released_DESC&tags=492&category1=10&os=linux",
  "location": "search.ts",
  "maintainers": [
    "moppman"
  ],
  "module": "() => import('@/routes/steam/search.ts')",
  "name": "Store Search",
  "parameters": {
    "params": "Query parameters for a Steam Store search."
  },
  "path": "/search/:params",
  "radar": [
    {
      "source": [
        "store.steampowered.com",
        "store.steampowered.com/search/:params"
      ]
    }
  ]
}
```
