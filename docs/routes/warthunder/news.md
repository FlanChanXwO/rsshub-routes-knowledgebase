# War Thunder - News

## Coverage
`index-only`

## Route
- Namespace: `warthunder`
- Namespace Name: `War Thunder`
- Route Path: `/news`
- Route Name: `News`
- Example: `/warthunder/news`
- URL: `warthunder.com/en/news`
- Language: `en`
- Categories: `game`
- Maintainers: `axojhf`
- Source Location: `news.tsx`
- Source Module: `() => import('@/routes/warthunder/news.tsx')`

## Description
News data from [https://warthunder.com/en/news/](https://warthunder.com/en/news/)
  The `pubDate` provided under UTC time zone, so please ignore the specific time!!!

## Parameters
_None_


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
  - `warthunder.com/en/news`
  - `warthunder.com/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "News data from [https://warthunder.com/en/news/](https://warthunder.com/en/news/)\n  The `pubDate` provided under UTC time zone, so please ignore the specific time!!!",
  "example": "/warthunder/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.tsx",
  "maintainers": [
    "axojhf"
  ],
  "module": "() => import('@/routes/warthunder/news.tsx')",
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "warthunder.com/en/news",
        "warthunder.com/"
      ]
    }
  ],
  "url": "warthunder.com/en/news"
}
```
