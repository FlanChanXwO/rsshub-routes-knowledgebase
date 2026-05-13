# Patreon - Home

## Coverage
`index-only`

## Route
- Namespace: `patreon`
- Namespace Name: `Patreon`
- Route Path: `/:creator`
- Route Name: `Home`
- Example: `/patreon/straightupsisters`
- URL: `www.patreon.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `feed.tsx`
- Source Module: `() => import('@/routes/patreon/feed.tsx')`

## Description
_None_

## Parameters
- `creator`: Patreon creator id, can be found in the url


## Features
- `requireConfig`: [{"description": "The value of the session_id cookie after logging in to Patreon, required to access paid posts", "name": "PATREON_SESSION_ID", "optional": true}]
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `patreon.com/:creator`
  - `www.patreon.com/cw/:creator`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/patreon/straightupsisters",
  "features": {
    "nsfw": true,
    "requireConfig": [
      {
        "description": "The value of the session_id cookie after logging in to Patreon, required to access paid posts",
        "name": "PATREON_SESSION_ID",
        "optional": true
      }
    ]
  },
  "location": "feed.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/patreon/feed.tsx')",
  "name": "Home",
  "parameters": {
    "creator": "Patreon creator id, can be found in the url"
  },
  "path": "/:creator",
  "radar": [
    {
      "source": [
        "patreon.com/:creator",
        "www.patreon.com/cw/:creator"
      ]
    }
  ]
}
```
