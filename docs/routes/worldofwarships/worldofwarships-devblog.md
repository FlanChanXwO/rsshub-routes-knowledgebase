# World of Warships - Development Blog

## Coverage
`index-only`

## Route
- Namespace: `worldofwarships`
- Namespace Name: `World of Warships`
- Route Path: `/worldofwarships/devblog`
- Route Name: `Development Blog`
- Example: `/worldofwarships/devblog`
- URL: `worldofwarships.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `SinCerely023`
- Source Location: `devblog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `blog.worldofwarships.com`
- `target`: `/devblog`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/worldofwarships/devblog",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "devblog.ts",
  "maintainers": [
    "SinCerely023"
  ],
  "name": "Development Blog",
  "path": "/devblog",
  "radar": [
    {
      "source": [
        "blog.worldofwarships.com"
      ],
      "target": "/devblog"
    }
  ],
  "topFeeds": [
    {
      "description": "World of Warships - Development Blog - Powered by RSSHub",
      "errorAt": "2024-12-02T13:43:22.875Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "85355522307031040",
      "image": "https://wows-web-static.wgcdn.co/wowsblog/f604319d/images/favicons/wows/blog_apple_touch_180.png",
      "ownerUserId": null,
      "siteUrl": "https://blog.worldofwarships.com/",
      "title": "World of Warships - Development Blog",
      "type": "feed",
      "url": "rsshub://worldofwarships/devblog"
    }
  ]
}
```
