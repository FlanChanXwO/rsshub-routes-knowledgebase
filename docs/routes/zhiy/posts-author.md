# 知园 - 笔记

## Coverage
`index-only`

## Route
- Namespace: `zhiy`
- Namespace Name: `知园`
- Route Path: `/posts/:author`
- Route Name: `笔记`
- Example: `/zhiy/posts/long`
- URL: `zhiy.cc`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `post.tsx`
- Source Module: `() => import('@/routes/zhiy/post.tsx')`

## Description
_None_

## Parameters
- `author`: 作者 ID，可在URL中找到


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
  - `zhiy.cc/:author`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/zhiy/posts/long",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "post.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/zhiy/post.tsx')",
  "name": "笔记",
  "parameters": {
    "author": "作者 ID，可在URL中找到"
  },
  "path": "/posts/:author",
  "radar": [
    {
      "source": [
        "zhiy.cc/:author"
      ]
    }
  ]
}
```
