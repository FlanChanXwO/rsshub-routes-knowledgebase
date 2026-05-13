# University of Washington - Global Innovation Exchange News

## Coverage
`index-only`

## Route
- Namespace: `uw`
- Namespace Name: `University of Washington`
- Route Path: `/gix/news/:category`
- Route Name: `Global Innovation Exchange News`
- Example: `/uw/gix/news/blog`
- URL: `gixnetwork.org`
- Language: `en`
- Categories: `university`
- Maintainers: `dykderrick`
- Source Location: `gix/news.ts`
- Source Module: `() => import('@/routes/uw/gix/news.ts')`

## Description
| Blog | In The News |
| ---- | ----------- |
| blog | inthenews   |

## Parameters
- `category`: Blog Type


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
  - `gixnetwork.org/news/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| Blog | In The News |\n| ---- | ----------- |\n| blog | inthenews   |",
  "example": "/uw/gix/news/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gix/news.ts",
  "maintainers": [
    "dykderrick"
  ],
  "module": "() => import('@/routes/uw/gix/news.ts')",
  "name": "Global Innovation Exchange News",
  "parameters": {
    "category": "Blog Type"
  },
  "path": "/gix/news/:category",
  "radar": [
    {
      "source": [
        "gixnetwork.org/news/:category"
      ]
    }
  ]
}
```
