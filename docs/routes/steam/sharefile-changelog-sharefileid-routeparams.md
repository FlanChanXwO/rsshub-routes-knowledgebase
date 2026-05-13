# Steam - Sharefile Changelog

## Coverage
`index-only`

## Route
- Namespace: `steam`
- Namespace Name: `Steam`
- Route Path: `/sharefile-changelog/:sharefileID/:routeParams?`
- Route Name: `Sharefile Changelog`
- Example: `/steam/sharefile-changelog/2851063440/l=schinese`
- URL: `store.steampowered.com`
- Language: `en`
- Categories: `game`
- Maintainers: `NyaaaDoge`
- Source Location: `sharefile-changelog.ts`
- Source Module: `() => import('@/routes/steam/sharefile-changelog.ts')`

## Description
Steam Community Sharefile's Changelog. Primary used for a workshop item.
Helpful route parameters:
- `l=` language parameter, change the language of description.
- `p=` page parameter, change the results page. p=1 by default.

## Parameters
- `sharefileID`: Steam community sharefile id. Usually refers to a workshop item.
- `routeParams`: Route parameters.


## Features
_None_

## Radar
### Rule 1
- `title`: `Sharefile Changelog`
- `source`:
  - `steamcommunity.com/sharedfiles/filedetails/changelog/:sharefileID`
- `target`: `/sharefile-changelog/:sharefileID`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Steam Community Sharefile's Changelog. Primary used for a workshop item.\nHelpful route parameters:\n- `l=` language parameter, change the language of description.\n- `p=` page parameter, change the results page. p=1 by default.\n",
  "example": "/steam/sharefile-changelog/2851063440/l=schinese",
  "location": "sharefile-changelog.ts",
  "maintainers": [
    "NyaaaDoge"
  ],
  "module": "() => import('@/routes/steam/sharefile-changelog.ts')",
  "name": "Sharefile Changelog",
  "parameters": {
    "routeParams": "Route parameters.",
    "sharefileID": "Steam community sharefile id. Usually refers to a workshop item."
  },
  "path": "/sharefile-changelog/:sharefileID/:routeParams?",
  "radar": [
    {
      "source": [
        "steamcommunity.com/sharedfiles/filedetails/changelog/:sharefileID"
      ],
      "target": "/sharefile-changelog/:sharefileID",
      "title": "Sharefile Changelog"
    }
  ]
}
```
