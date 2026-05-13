# Steam - Steam Community Hub Feeds

## Coverage
`index-only`

## Route
- Namespace: `steam`
- Namespace Name: `Steam`
- Route Path: `/appcommunityfeed/:appid/:routeParams?`
- Route Name: `Steam Community Hub Feeds`
- Example: `/steam/appcommunityfeed/730`
- URL: `store.steampowered.com`
- Language: `en`
- Categories: `game`
- Maintainers: `NyaaaDoge`
- Source Location: `appcommunityfeed.tsx`
- Source Module: `() => import('@/routes/steam/appcommunityfeed.tsx')`

## Description
Query Parameters:

| Name                   | Type   | Description             |
| ---------------------- | ------ | ----------------------- |
| p                      | string | p                       |
| rgSections[]           | string | rgSections              |
| filterLanguage         | string | Filter Language         |
| languageTag            | string | Language Tag            |
| nMaxInappropriateScore | string | Max Inappropriate Score |

Example:
- `/appcommunityfeed/730/p=1&rgSections[]=2&rgSections[]=4&filterLanguage=english&languageTag=english&nMaxInappropriateScore=1` for CS2 Screenshot and Artwork contents.
- `/appcommunityfeed/730/rgSections[]=6` for CS2 Workshop contents only.
- `/appcommunityfeed/570/rgSections[]=3&rgSections[]=9` for Dota2 Video and Guides contents.

::: tip
It can also access community hub contents that require a logged-in account.
:::

## Parameters
- `appid`: Steam appid, can be found on the community hub page or store page URL.
- `routeParams`: Query parameters.


## Features
_None_

## Radar
### Rule 1
- `title`: `Community Hub`
- `source`:
  - `steamcommunity.com/app/:appid`
- `target`: `/appcommunityfeed/:appid`
### Rule 2
- `title`: `Community Hub`
- `source`:
  - `store.steampowered.com/app/:appid/*/`
- `target`: `/appcommunityfeed/:appid`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Query Parameters:\n\n| Name                   | Type   | Description             |\n| ---------------------- | ------ | ----------------------- |\n| p                      | string | p                       |\n| rgSections[]           | string | rgSections              |\n| filterLanguage         | string | Filter Language         |\n| languageTag            | string | Language Tag            |\n| nMaxInappropriateScore | string | Max Inappropriate Score |\n\nExample:\n- `/appcommunityfeed/730/p=1&rgSections[]=2&rgSections[]=4&filterLanguage=english&languageTag=english&nMaxInappropriateScore=1` for CS2 Screenshot and Artwork contents.\n- `/appcommunityfeed/730/rgSections[]=6` for CS2 Workshop contents only.\n- `/appcommunityfeed/570/rgSections[]=3&rgSections[]=9` for Dota2 Video and Guides contents.\n\n::: tip\nIt can also access community hub contents that require a logged-in account.\n:::\n",
  "example": "/steam/appcommunityfeed/730",
  "location": "appcommunityfeed.tsx",
  "maintainers": [
    "NyaaaDoge"
  ],
  "module": "() => import('@/routes/steam/appcommunityfeed.tsx')",
  "name": "Steam Community Hub Feeds",
  "parameters": {
    "appid": "Steam appid, can be found on the community hub page or store page URL.",
    "routeParams": "Query parameters."
  },
  "path": "/appcommunityfeed/:appid/:routeParams?",
  "radar": [
    {
      "source": [
        "steamcommunity.com/app/:appid"
      ],
      "target": "/appcommunityfeed/:appid",
      "title": "Community Hub"
    },
    {
      "source": [
        "store.steampowered.com/app/:appid/*/"
      ],
      "target": "/appcommunityfeed/:appid",
      "title": "Community Hub"
    }
  ]
}
```
