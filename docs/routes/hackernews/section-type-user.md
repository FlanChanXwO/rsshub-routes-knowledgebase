# Hacker News - User

## Coverage
`index-only`

## Route
- Namespace: `hackernews`
- Namespace Name: `Hacker News`
- Route Path: `/:section?/:type?/:user?`
- Route Name: `User`
- Example: `/hackernews/threads/comments_list/dang`
- URL: `ycombinator.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `nczitzk, xie-dongping`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/hackernews/index.ts')`

## Description
Subscribe to the content of a specific user

## Parameters
- `section`: {"description": "Content section, default to `index`"}
- `type`: {"description": "Link type, default to `sources`"}
- `user`: {"description": "Set user, only valid in `threads` and `submitted` sections"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `news.ycombinator.com/:section`
  - `news.ycombinator.com/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "Subscribe to the content of a specific user",
  "example": "/hackernews/threads/comments_list/dang",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "xie-dongping"
  ],
  "module": "() => import('@/routes/hackernews/index.ts')",
  "name": "User",
  "parameters": {
    "section": {
      "description": "Content section, default to `index`"
    },
    "type": {
      "description": "Link type, default to `sources`"
    },
    "user": {
      "description": "Set user, only valid in `threads` and `submitted` sections"
    }
  },
  "path": "/:section?/:type?/:user?",
  "radar": [
    {
      "source": [
        "news.ycombinator.com/:section",
        "news.ycombinator.com/"
      ]
    }
  ],
  "view": 0
}
```
