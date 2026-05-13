# 知园 - 笔记

## Coverage
`index-only`

## Route
- Namespace: `zhiy`
- Namespace Name: `知园`
- Route Path: `/zhiy/posts/:author`
- Route Name: `笔记`
- Example: `/zhiy/posts/long`
- URL: `zhiy.cc`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `post.tsx`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "post.tsx",
  "maintainers": [
    "TonyRL"
  ],
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
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
