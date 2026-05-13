# V2EX - 帖子

## Coverage
`index-only`

## Route
- Namespace: `v2ex`
- Namespace Name: `V2EX`
- Route Path: `/post/:postid`
- Route Name: `帖子`
- Example: `/v2ex/post/584403`
- URL: `v2ex.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `kt286`
- Source Location: `post.ts`
- Source Module: `() => import('@/routes/v2ex/post.ts')`

## Description
_None_

## Parameters
- `postid`: 帖子ID，在 URL 可以找到


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
  - `v2ex.com/t/:postid`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/v2ex/post/584403",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "post.ts",
  "maintainers": [
    "kt286"
  ],
  "module": "() => import('@/routes/v2ex/post.ts')",
  "name": "帖子",
  "parameters": {
    "postid": "帖子ID，在 URL 可以找到"
  },
  "path": "/post/:postid",
  "radar": [
    {
      "source": [
        "v2ex.com/t/:postid"
      ]
    }
  ]
}
```
