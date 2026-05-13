# Letterboxd - User Watchlist

## Coverage
`index-only`

## Route
- Namespace: `letterboxd`
- Namespace Name: `Letterboxd`
- Route Path: `/:username/watchlist`
- Route Name: `User Watchlist`
- Example: `/letterboxd/matthew/watchlist`
- URL: `letterboxd.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `johan456789`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/letterboxd/index.ts')`

## Description
_None_

## Parameters
- `username`: Letterboxd username


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `letterboxd.com/:username/watchlist/`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/letterboxd/matthew/watchlist",
  "location": "index.ts",
  "maintainers": [
    "johan456789"
  ],
  "module": "() => import('@/routes/letterboxd/index.ts')",
  "name": "User Watchlist",
  "parameters": {
    "username": "Letterboxd username"
  },
  "path": "/:username/watchlist",
  "radar": [
    {
      "source": [
        "letterboxd.com/:username/watchlist/"
      ]
    }
  ],
  "url": "letterboxd.com"
}
```
