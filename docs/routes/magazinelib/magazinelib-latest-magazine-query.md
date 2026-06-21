# MagazineLib - Latest Magazine

## Coverage
`index-only`

## Route
- Namespace: `magazinelib`
- Namespace Name: `MagazineLib`
- Route Path: `/magazinelib/latest-magazine/:query?`
- Route Name: `Latest Magazine`
- Example: `/magazinelib/latest-magazine/new+yorker`
- URL: `magazinelib.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `EthanWng97`
- Source Location: `latest-magazine.tsx`
- Source Module: `_None_`

## Description
For instance, when doing search at <https://magazinelib.com> and you get url `https://magazinelib.com/?s=new+yorker`, the query is `new+yorker`

## Parameters
- `query`: query, search page querystring


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "For instance, when doing search at <https://magazinelib.com> and you get url `https://magazinelib.com/?s=new+yorker`, the query is `new+yorker`",
  "example": "/magazinelib/latest-magazine/new+yorker",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "latest-magazine.tsx",
  "maintainers": [
    "EthanWng97"
  ],
  "name": "Latest Magazine",
  "parameters": {
    "query": "query, search page querystring"
  },
  "path": "/latest-magazine/:query?",
  "topFeeds": [
    {
      "description": "MagazineLib - Latest Magazines - NEW YORKER - Powered by RSSHub",
      "errorAt": "2026-06-19T16:22:54.214Z",
      "errorMessage": "[GET] \"https://magazinelib.com/wp-json/wp/v2/posts/?search=new+yorker&per_page=30&_embed=1\": 403 Forbidden\n",
      "id": "258938409787591680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://magazinelib.com/?s=new%20yorker",
      "title": "MagazineLib - Latest Magazines - NEW YORKER",
      "type": "feed",
      "url": "rsshub://magazinelib/latest-magazine/new%20yorker"
    }
  ]
}
```
