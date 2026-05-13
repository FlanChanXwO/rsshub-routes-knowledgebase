# Bluesky (bsky) - Post

## Coverage
`index-only`

## Route
- Namespace: `bsky`
- Namespace Name: `Bluesky (bsky)`
- Route Path: `/profile/:handle/:routeParams?`
- Route Name: `Post`
- Example: `/bsky/profile/bsky.app`
- URL: `bsky.app`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `posts.ts`
- Source Module: `() => import('@/routes/bsky/posts.ts')`

## Description
| Filter Value | Description |
|--------------|-------------|
| posts_with_replies | Includes Posts, Replies, and Reposts |
| posts_no_replies | Includes Posts and Reposts, without Replies |
| posts_with_media | Shows only Posts containing media |
| posts_and_author_threads | Shows Posts and Threads, without Replies and Reposts |

Default value for filter is `posts_and_author_threads` if not specified.

Example:
- `/bsky/profile/bsky.app/filter=posts_with_replies`

## Parameters
- `handle`: User handle, can be found in URL
- `routeParams`: Filter parameter, Use filter to customize content types


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
  - `bsky.app/profile/:handle`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "\n| Filter Value | Description |\n|--------------|-------------|\n| posts_with_replies | Includes Posts, Replies, and Reposts |\n| posts_no_replies | Includes Posts and Reposts, without Replies |\n| posts_with_media | Shows only Posts containing media |\n| posts_and_author_threads | Shows Posts and Threads, without Replies and Reposts |\n\nDefault value for filter is `posts_and_author_threads` if not specified.\n\nExample:\n- `/bsky/profile/bsky.app/filter=posts_with_replies`",
  "example": "/bsky/profile/bsky.app",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "posts.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/bsky/posts.ts')",
  "name": "Post",
  "parameters": {
    "handle": "User handle, can be found in URL",
    "routeParams": "Filter parameter, Use filter to customize content types"
  },
  "path": "/profile/:handle/:routeParams?",
  "radar": [
    {
      "source": [
        "bsky.app/profile/:handle"
      ]
    }
  ],
  "view": 1
}
```
