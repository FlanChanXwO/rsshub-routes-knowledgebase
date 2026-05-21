# War Thunder - News

## Coverage
`index-only`

## Route
- Namespace: `warthunder`
- Namespace Name: `War Thunder`
- Route Path: `/warthunder/news`
- Route Name: `News`
- Example: `/warthunder/news`
- URL: `warthunder.com/en/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `axojhf`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
News data from <https://warthunder.com/en/news/>
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
  "description": "News data from <https://warthunder.com/en/news/>\nThe `pubDate` provided under UTC time zone, so please ignore the specific time!!!",
  "example": "/warthunder/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "news.tsx",
  "maintainers": [
    "axojhf"
  ],
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
  "topFeeds": [
    {
      "description": "War Thunder News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74063151402982400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://warthunder.com/en/news/",
      "title": "War Thunder News",
      "type": "feed",
      "url": "rsshub://warthunder/news"
    }
  ],
  "url": "warthunder.com/en/news"
}
```
