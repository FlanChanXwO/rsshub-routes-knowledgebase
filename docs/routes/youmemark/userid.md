# YouMeMark - Bookmarks

## Coverage
`index-only`

## Route
- Namespace: `youmemark`
- Namespace Name: `YouMeMark`
- Route Path: `/:userid`
- Route Name: `Bookmarks`
- Example: `/youmemark/pseudoyu`
- URL: `youmemark.com`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/youmemark/index.ts')`

## Description
Get user's public bookmarks from YouMeMark
::: tip
  Add `?limit=<number>` to the end of the route to limit the number of items. Default is 10.
:::

## Parameters
- `userid`: `userid` is the user id of youmemark


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
  - `youmemark.com/user/:userid`
- `target`: `/:userid`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "Get user's public bookmarks from YouMeMark\n::: tip\n  Add `?limit=<number>` to the end of the route to limit the number of items. Default is 10.\n:::",
  "example": "/youmemark/pseudoyu",
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
    "pseudoyu"
  ],
  "module": "() => import('@/routes/youmemark/index.ts')",
  "name": "Bookmarks",
  "parameters": {
    "userid": "`userid` is the user id of youmemark"
  },
  "path": "/:userid",
  "radar": [
    {
      "source": [
        "youmemark.com/user/:userid"
      ],
      "target": "/:userid"
    }
  ]
}
```
