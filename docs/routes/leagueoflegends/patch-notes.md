# League of Legends - Patch Notes

## Coverage
`index-only`

## Route
- Namespace: `leagueoflegends`
- Namespace Name: `League of Legends`
- Route Path: `/patch-notes`
- Route Name: `Patch Notes`
- Example: `/leagueoflegends/patch-notes`
- URL: `leagueoflegends.com`
- Language: `en`
- Categories: `game`
- Maintainers: `noahm`
- Source Location: `patch-notes.ts`
- Source Module: `() => import('@/routes/leagueoflegends/patch-notes.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.leagueoflegends.com/en-us/news/tags/patch-notes/`
  - `www.leagueoflegends.com/en-us/news/game-updates/:postSlug`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/leagueoflegends/patch-notes",
  "location": "patch-notes.ts",
  "maintainers": [
    "noahm"
  ],
  "module": "() => import('@/routes/leagueoflegends/patch-notes.ts')",
  "name": "Patch Notes",
  "path": "/patch-notes",
  "radar": [
    {
      "source": [
        "www.leagueoflegends.com/en-us/news/tags/patch-notes/",
        "www.leagueoflegends.com/en-us/news/game-updates/:postSlug"
      ]
    }
  ]
}
```
