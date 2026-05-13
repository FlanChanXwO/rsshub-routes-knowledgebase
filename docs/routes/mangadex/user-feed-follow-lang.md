# MangaDex - Follows Feed

## Coverage
`index-only`

## Route
- Namespace: `mangadex`
- Namespace Name: `MangaDex`
- Route Path: `/user/feed/follow/:lang?`
- Route Name: `Follows Feed`
- Example: `/mangadex/user/feed/follow/zh?limit=10`
- URL: `mangadex.org`
- Language: `en`
- Categories: `anime`
- Maintainers: `chrisis58`
- Source Location: `user/feed.ts`
- Source Module: `() => import('@/routes/mangadex/user/feed.ts')`

## Description
Get the latest updates of all the manga you follow on MangaDex.

## Parameters
- `lang`: {"description": "The language of the followed manga"}


## Features
- `requireConfig`: [{"description": "MangaDex Username, required when refresh-token is not set", "name": "MANGADEX_USERNAME", "optional": true}, {"description": "MangaDex Password, required when refresh-token is not set", "name": "MANGADEX_PASSWORD", "optional": true}, {"description": "MangaDex Client ID", "name": "MANGADEX_CLIENT_ID", "optional": false}, {"description": "MangaDex Client Secret", "name": "MANGADEX_CLIENT_SECRET", "optional": false}, {"description": "MangaDex Refresh Token, required when username and password are not set", "name": "MANGADEX_REFRESH_TOKEN", "optional": true}]
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `mangadex.org/titles/feed`
- `target`: `/user/feed/follow`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "Get the latest updates of all the manga you follow on MangaDex.",
  "example": "/mangadex/user/feed/follow/zh?limit=10",
  "features": {
    "nsfw": true,
    "requireConfig": [
      {
        "description": "MangaDex Username, required when refresh-token is not set",
        "name": "MANGADEX_USERNAME",
        "optional": true
      },
      {
        "description": "MangaDex Password, required when refresh-token is not set",
        "name": "MANGADEX_PASSWORD",
        "optional": true
      },
      {
        "description": "MangaDex Client ID",
        "name": "MANGADEX_CLIENT_ID",
        "optional": false
      },
      {
        "description": "MangaDex Client Secret",
        "name": "MANGADEX_CLIENT_SECRET",
        "optional": false
      },
      {
        "description": "MangaDex Refresh Token, required when username and password are not set",
        "name": "MANGADEX_REFRESH_TOKEN",
        "optional": true
      }
    ]
  },
  "location": "user/feed.ts",
  "maintainers": [
    "chrisis58"
  ],
  "module": "() => import('@/routes/mangadex/user/feed.ts')",
  "name": " Follows Feed",
  "parameters": {
    "lang": {
      "description": "The language of the followed manga"
    }
  },
  "path": "/user/feed/follow/:lang?",
  "radar": [
    {
      "source": [
        "mangadex.org/titles/feed"
      ],
      "target": "/user/feed/follow"
    }
  ]
}
```
