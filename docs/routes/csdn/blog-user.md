# CSDN - User Feed

## Coverage
`index-only`

## Route
- Namespace: `csdn`
- Namespace Name: `CSDN`
- Route Path: `/blog/:user`
- Route Name: `User Feed`
- Example: `/csdn/blog/csdngeeknews`
- URL: `blog.csdn.net`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `Jkker`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/csdn/blog.ts')`

## Description
_None_

## Parameters
- `user`: `user` is the username of a CSDN blog which can be found in the url of the home page


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
  - `blog.csdn.net/:user`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/csdn/blog/csdngeeknews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blog.ts",
  "maintainers": [
    "Jkker"
  ],
  "module": "() => import('@/routes/csdn/blog.ts')",
  "name": "User Feed",
  "parameters": {
    "user": "`user` is the username of a CSDN blog which can be found in the url of the home page"
  },
  "path": "/blog/:user",
  "radar": [
    {
      "source": [
        "blog.csdn.net/:user"
      ]
    }
  ]
}
```
