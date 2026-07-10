# 台灣角川 - 角編新聞台

## Coverage
`index-only`

## Route
- Namespace: `kadokawa`
- Namespace Name: `台灣角川`
- Route Path: `/kadokawa/blog`
- Route Name: `角編新聞台`
- Example: `/kadokawa/blog`
- URL: `kadokawa.com.tw`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `kadokawa.com.tw/blog/posts`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "",
  "example": "/kadokawa/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 12,
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "角編新聞台",
  "path": "/blog",
  "radar": [
    {
      "source": [
        "kadokawa.com.tw/blog/posts"
      ],
      "target": "/blog"
    }
  ],
  "topFeeds": [
    {
      "description": "角編新聞台 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71823730235321344",
      "image": "https://img.shoplineapp.com/media/image_clips/655dc2a5145a54001432df3c/original.png?1700643493",
      "ownerUserId": null,
      "siteUrl": "https://www.kadokawa.com.tw/blog/posts",
      "title": "角編新聞台",
      "type": "feed",
      "url": "rsshub://kadokawa/blog"
    }
  ],
  "url": "kadokawa.com.tw"
}
```
