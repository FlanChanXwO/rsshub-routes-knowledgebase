# Steam - Community Workshop Search

## Coverage
`index-only`

## Route
- Namespace: `steam`
- Namespace Name: `Steam`
- Route Path: `/workshopsearch/:appid?/:routeParams?`
- Route Name: `Community Workshop Search`
- Example: `/steam/workshopsearch/730`
- URL: `store.steampowered.com`
- Language: `en`
- Categories: `game`
- Maintainers: `NyaaaDoge`
- Source Location: `workshop-search.tsx`
- Source Module: `() => import('@/routes/steam/workshop-search.tsx')`

## Description
Steam Community Workshop Search Results.
The parameter 'l=language' changes the language of search results(if possible).
For example, route `/workshopsearch/730/l=schinese` will display the simplified Chinese descriptions of the entry.

Language Parameter:

| English | 简体中文 | 繁體中文 | 日本語   | 한국어  | ภาษาไทย | български | čeština | dansk  | Deutsch | español | latam | ελληνικά | français | italiano | Bahasa Indonesia | magyar    | Nederlands | norsk     | polski | português  | brasileiro | română   | русский | suomi   | svenska | Türkçe  | Tiếng Việt | українська |
| ------- | -------- | -------- | -------- | ------- | ------- | --------- | ------- | ------ | ------- | ------- | ----- | -------- | -------- | -------- | ---------------- | --------- | ---------- | --------- | ------ | ---------- | ---------- | -------- | ------- | ------- | ------- | ------- | ---------- | ---------- |
| english | schinese | tchinese | japanese | koreana | thai    | bulgarian | czech   | danish | german  | spanish | latam | greek    | french   | italian  | indonesian       | hungarian | dutch      | norwegian | polish | portuguese | brazilian  | romanian | russian | finnish | swedish | turkish | vietnamese | ukrainian  |

## Parameters
- `appid`: Steam appid, can be found on the community hub page or store page URL, 730 by default.
- `routeParams`: Route parameters, can be found on the search result page URL. Route parameters located after the appid.


## Features
_None_

## Radar
### Rule 1
- `title`: `Workshop Search Results`
- `source`:
  - `steamcommunity.com/app/:appid/workshop/`
- `target`: `/workshopsearch/:appid`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Steam Community Workshop Search Results.\nThe parameter 'l=language' changes the language of search results(if possible).\nFor example, route `/workshopsearch/730/l=schinese` will display the simplified Chinese descriptions of the entry.\n\nLanguage Parameter:\n\n| English | 简体中文 | 繁體中文 | 日本語   | 한국어  | ภาษาไทย | български | čeština | dansk  | Deutsch | español | latam | ελληνικά | français | italiano | Bahasa Indonesia | magyar    | Nederlands | norsk     | polski | português  | brasileiro | română   | русский | suomi   | svenska | Türkçe  | Tiếng Việt | українська |\n| ------- | -------- | -------- | -------- | ------- | ------- | --------- | ------- | ------ | ------- | ------- | ----- | -------- | -------- | -------- | ---------------- | --------- | ---------- | --------- | ------ | ---------- | ---------- | -------- | ------- | ------- | ------- | ------- | ---------- | ---------- |\n| english | schinese | tchinese | japanese | koreana | thai    | bulgarian | czech   | danish | german  | spanish | latam | greek    | french   | italian  | indonesian       | hungarian | dutch      | norwegian | polish | portuguese | brazilian  | romanian | russian | finnish | swedish | turkish | vietnamese | ukrainian  |\n\n",
  "example": "/steam/workshopsearch/730",
  "location": "workshop-search.tsx",
  "maintainers": [
    "NyaaaDoge"
  ],
  "module": "() => import('@/routes/steam/workshop-search.tsx')",
  "name": "Community Workshop Search",
  "parameters": {
    "appid": "Steam appid, can be found on the community hub page or store page URL, 730 by default.",
    "routeParams": "Route parameters, can be found on the search result page URL. Route parameters located after the appid."
  },
  "path": "/workshopsearch/:appid?/:routeParams?",
  "radar": [
    {
      "source": [
        "steamcommunity.com/app/:appid/workshop/"
      ],
      "target": "/workshopsearch/:appid",
      "title": "Workshop Search Results"
    }
  ]
}
```
