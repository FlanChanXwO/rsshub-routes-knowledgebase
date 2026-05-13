# MangaDex - Logged User's Followed Mangas Feed

## Coverage
`index-only`

## Route
- Namespace: `mangadex`
- Namespace Name: `MangaDex`
- Route Path: `/user/follow/:type?`
- Route Name: `Logged User's Followed Mangas Feed`
- Example: `/mangadex/user/follow/reading`
- URL: `mangadex.org`
- Language: `en`
- Categories: `anime`
- Maintainers: `chrisis58`
- Source Location: `user/follows.ts`
- Source Module: `() => import('@/routes/mangadex/user/follows.ts')`

## Description
Fetches the feed of mangas that you follow on MangaDex whick are in the specified status.
CAUTION: With big amount of follows, it may take a long time to load or even fail.
It's recommended to use the `/mangadex/mdlist/:listId?` route instead for better performance, though it requires manual configuration.

## Parameters
- `type`: {"default": "reading", "description": "The type of follows to fetch", "options": [{"label": "Reading", "value": "reading"}, {"label": "Plan to Read", "value": "plan-to-read"}, {"label": "Completed", "value": "completed"}, {"label": "On Hold", "value": "on-hold"}, {"label": "Re-reading", "value": "re-reading"}, {"label": "Dropped", "value": "dropped"}]}


## Features
- `requireConfig`: [{"description": "MangaDex Username, required when refresh-token is not set", "name": "MANGADEX_USERNAME", "optional": true}, {"description": "MangaDex Password, required when refresh-token is not set", "name": "MANGADEX_PASSWORD", "optional": true}, {"description": "MangaDex Client ID", "name": "MANGADEX_CLIENT_ID", "optional": false}, {"description": "MangaDex Client Secret", "name": "MANGADEX_CLIENT_SECRET", "optional": false}, {"description": "MangaDex Refresh Token, required when username and password are not set", "name": "MANGADEX_REFRESH_TOKEN", "optional": true}]
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `mangadex.org/titles/follows`
- `target`: `/user/follow/reading`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "Fetches the feed of mangas that you follow on MangaDex whick are in the specified status.\nCAUTION: With big amount of follows, it may take a long time to load or even fail.\nIt's recommended to use the `/mangadex/mdlist/:listId?` route instead for better performance, though it requires manual configuration.",
  "example": "/mangadex/user/follow/reading",
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
  "location": "user/follows.ts",
  "maintainers": [
    "chrisis58"
  ],
  "module": "() => import('@/routes/mangadex/user/follows.ts')",
  "name": "Logged User's Followed Mangas Feed",
  "parameters": {
    "type": {
      "default": "reading",
      "description": "The type of follows to fetch",
      "options": [
        {
          "label": "Reading",
          "value": "reading"
        },
        {
          "label": "Plan to Read",
          "value": "plan-to-read"
        },
        {
          "label": "Completed",
          "value": "completed"
        },
        {
          "label": "On Hold",
          "value": "on-hold"
        },
        {
          "label": "Re-reading",
          "value": "re-reading"
        },
        {
          "label": "Dropped",
          "value": "dropped"
        }
      ]
    }
  },
  "path": "/user/follow/:type?",
  "radar": [
    {
      "source": [
        "mangadex.org/titles/follows"
      ],
      "target": "/user/follow/reading"
    }
  ]
}
```
