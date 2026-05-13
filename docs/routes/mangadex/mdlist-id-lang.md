# MangaDex - MDList Feed

## Coverage
`index-only`

## Route
- Namespace: `mangadex`
- Namespace Name: `MangaDex`
- Route Path: `/mdlist/:id/:lang?`
- Route Name: `MDList Feed`
- Example: `/mangadex/mdlist/10cca803-8dc9-4f0e-86a8-6659a3ce5188?limit=10&private=true`
- URL: `mangadex.org`
- Language: `en`
- Categories: `anime`
- Maintainers: `chrisis58`
- Source Location: `mdlist/feed.ts`
- Source Module: `() => import('@/routes/mangadex/mdlist/feed.ts')`

## Description
Sepcific MangaDex MDList Feed

## Parameters
- `id`: {"description": "The list id of the manga list"}
- `private`: {"description": "(Query Param) Needed to access private lists, any value will be treated as true"}


## Features
- `requireConfig`: [{"description": "MangaDex Username, required when refresh-token is not set and the list is private", "name": "MANGADEX_USERNAME", "optional": true}, {"description": "MangaDex Password, required when refresh-token is not set and the list is private", "name": "MANGADEX_PASSWORD", "optional": true}, {"description": "MangaDex Client ID, required when the list is private", "name": "MANGADEX_CLIENT_ID", "optional": true}, {"description": "MangaDex Client Secret, required when the list is private", "name": "MANGADEX_CLIENT_SECRET", "optional": true}, {"description": "MangaDex Refresh Token, required when username and password are not set and the list is private", "name": "MANGADEX_REFRESH_TOKEN", "optional": true}]
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `mangadex.org/list/:id/:suffix`
- `target`: `/mdlist/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "Sepcific MangaDex MDList Feed",
  "example": "/mangadex/mdlist/10cca803-8dc9-4f0e-86a8-6659a3ce5188?limit=10&private=true",
  "features": {
    "nsfw": true,
    "requireConfig": [
      {
        "description": "MangaDex Username, required when refresh-token is not set and the list is private",
        "name": "MANGADEX_USERNAME",
        "optional": true
      },
      {
        "description": "MangaDex Password, required when refresh-token is not set and the list is private",
        "name": "MANGADEX_PASSWORD",
        "optional": true
      },
      {
        "description": "MangaDex Client ID, required when the list is private",
        "name": "MANGADEX_CLIENT_ID",
        "optional": true
      },
      {
        "description": "MangaDex Client Secret, required when the list is private",
        "name": "MANGADEX_CLIENT_SECRET",
        "optional": true
      },
      {
        "description": "MangaDex Refresh Token, required when username and password are not set and the list is private",
        "name": "MANGADEX_REFRESH_TOKEN",
        "optional": true
      }
    ]
  },
  "location": "mdlist/feed.ts",
  "maintainers": [
    "chrisis58"
  ],
  "module": "() => import('@/routes/mangadex/mdlist/feed.ts')",
  "name": "MDList Feed",
  "parameters": {
    "id": {
      "description": "The list id of the manga list"
    },
    "private": {
      "description": "(Query Param) Needed to access private lists, any value will be treated as true"
    }
  },
  "path": "/mdlist/:id/:lang?",
  "radar": [
    {
      "source": [
        "mangadex.org/list/:id/:suffix"
      ],
      "target": "/mdlist/:id"
    }
  ]
}
```
