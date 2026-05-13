# Liquipedia - Counter-Strike Team Match Results

## Coverage
`index-only`

## Route
- Namespace: `liquipedia`
- Namespace Name: `Liquipedia`
- Route Path: `/counterstrike/matches/:team`
- Route Name: `Counter-Strike Team Match Results`
- Example: `/liquipedia/counterstrike/matches/Team_Falcons`
- URL: `liquipedia.net`
- Language: `en`
- Categories: `None`
- Maintainers: `CookiePieWw`
- Source Location: `cs-matches.ts`
- Source Module: `() => import('@/routes/liquipedia/cs-matches.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `liquipedia.net/counterstrike/:id/Matches`
  - `liquipedia.net/dota2/:id`
- `target`: `/counterstrike/matches/:id`

## Raw JSON
```json
{
  "example": "/liquipedia/counterstrike/matches/Team_Falcons",
  "location": "cs-matches.ts",
  "maintainers": [
    "CookiePieWw"
  ],
  "module": "() => import('@/routes/liquipedia/cs-matches.ts')",
  "name": "Counter-Strike Team Match Results",
  "path": "/counterstrike/matches/:team",
  "radar": [
    {
      "source": [
        "liquipedia.net/counterstrike/:id/Matches",
        "liquipedia.net/dota2/:id"
      ],
      "target": "/counterstrike/matches/:id"
    }
  ]
}
```
