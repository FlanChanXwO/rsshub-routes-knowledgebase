# Onet - News

## Coverage
`index-only`

## Route
- Namespace: `onet`
- Namespace Name: `Onet`
- Route Path: `/news`
- Route Name: `News`
- Example: `/onet/news`
- URL: `wiadomosci.onet.pl/`
- Language: `en`
- Categories: `new-media`
- Maintainers: `Vegann`
- Source Location: `news.tsx`
- Source Module: `() => import('@/routes/onet/news.tsx')`

## Description
This route provides a better reading experience (full text articles) over the official one for `https://wiadomosci.onet.pl`.

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
  - `wiadomosci.onet.pl/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "This route provides a better reading experience (full text articles) over the official one for `https://wiadomosci.onet.pl`.",
  "example": "/onet/news",
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
    "Vegann"
  ],
  "module": "() => import('@/routes/onet/news.tsx')",
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "wiadomosci.onet.pl/"
      ]
    }
  ],
  "url": "wiadomosci.onet.pl/"
}
```
