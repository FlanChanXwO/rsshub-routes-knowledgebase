# 4chan - Board's catalog

## Coverage
`index-only`

## Route
- Namespace: `4chan`
- Namespace Name: `4chan`
- Route Path: `/:board/catalog/:routeParams?`
- Route Name: `Board's catalog`
- Example: `/4chan/g/catalog`
- URL: `4chan.org`
- Language: `en`
- Categories: `bbs`
- Maintainers: `heisenshark`
- Source Location: `catalog.tsx`
- Source Module: `() => import('@/routes/4chan/catalog.tsx')`

## Description
Specify options (in the format of query string) in parameter `routeParams` to control some extra features for Tweets
| Key                            | Description                                                                                                                          | Accepts                | Defaults to                               |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ | ---------------------- | ----------------------------------------- |
| `showReplyCount`            | Show number of replies of each thread in catalog | `0`/`1`/`true`/`false` | `false` |
| `showLastReplies`            | Show last 5 replies of each thread | `0`/`1`/`true`/`false` | `false` |
| `revealSpoilers`            | Don't wrap images tagged as spoilers | `0`/`1`/`true`/`false` | `false` |

## Parameters
- `board`: 4chan board
- `routeParams`: extra parameters, see the table above


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `boards.4chan.org/:board/`
- `target`: `/:board/catalog`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "Specify options (in the format of query string) in parameter `routeParams` to control some extra features for Tweets\n| Key                            | Description                                                                                                                          | Accepts                | Defaults to                               |\n| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------ | ---------------------- | ----------------------------------------- |\n| `showReplyCount`            | Show number of replies of each thread in catalog | `0`/`1`/`true`/`false` | `false` |\n| `showLastReplies`            | Show last 5 replies of each thread | `0`/`1`/`true`/`false` | `false` |\n| `revealSpoilers`            | Don't wrap images tagged as spoilers | `0`/`1`/`true`/`false` | `false` |",
  "example": "/4chan/g/catalog",
  "features": {
    "antiCrawler": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "catalog.tsx",
  "maintainers": [
    "heisenshark"
  ],
  "module": "() => import('@/routes/4chan/catalog.tsx')",
  "name": "Board's catalog",
  "parameters": {
    "board": "4chan board",
    "routeParams": "extra parameters, see the table above"
  },
  "path": "/:board/catalog/:routeParams?",
  "radar": [
    {
      "source": [
        "boards.4chan.org/:board/"
      ],
      "target": "/:board/catalog"
    }
  ]
}
```
