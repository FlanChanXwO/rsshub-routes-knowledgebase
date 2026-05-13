# 1x.com - Gallery

## Coverage
`index-only`

## Route
- Namespace: `1x`
- Namespace Name: `1x.com`
- Route Path: `/:category{.+}?`
- Route Name: `Gallery`
- Example: `/1x/latest/awarded`
- URL: `1x.com`
- Language: `en`
- Categories: `design, picture`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/1x/index.tsx')`

## Description
::: tip
Fill in the field in the path with the part of the corresponding page URL after `https://1x.com/gallery/` or `https://1x.com/photo/`. Here are the examples:

If you subscribe to [Abstract Awarded](https://1x.com/gallery/abstract/awarded), you should fill in the path with the part `abstract/awarded` from the page URL `https://1x.com/gallery/abstract/awarded`. In this case, the route will be [`/1x/abstract/awarded`](https://rsshub.app/1x/abstract/awarded).

If you subscribe to [Wildlife Published](https://1x.com/gallery/wildlife/published), you should fill in the path with the part `wildlife/published` from the page URL `https://1x.com/gallery/wildlife/published`. In this case, the route will be [`/1x/wildlife/published`](https://rsshub.app/1x/wildlife/published).
:::

## Parameters
- `category`: Category, Latest Awarded by default


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
  - `/gallery/:category*`
  - `/photos/:category*`
- `target`: `/1x/:category`

## Raw JSON
```json
{
  "categories": [
    "design",
    "picture"
  ],
  "description": "::: tip\nFill in the field in the path with the part of the corresponding page URL after `https://1x.com/gallery/` or `https://1x.com/photo/`. Here are the examples:\n\nIf you subscribe to [Abstract Awarded](https://1x.com/gallery/abstract/awarded), you should fill in the path with the part `abstract/awarded` from the page URL `https://1x.com/gallery/abstract/awarded`. In this case, the route will be [`/1x/abstract/awarded`](https://rsshub.app/1x/abstract/awarded).\n\nIf you subscribe to [Wildlife Published](https://1x.com/gallery/wildlife/published), you should fill in the path with the part `wildlife/published` from the page URL `https://1x.com/gallery/wildlife/published`. In this case, the route will be [`/1x/wildlife/published`](https://rsshub.app/1x/wildlife/published).\n:::",
  "example": "/1x/latest/awarded",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/1x/index.tsx')",
  "name": "Gallery",
  "parameters": {
    "category": "Category, Latest Awarded by default"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "/gallery/:category*",
        "/photos/:category*"
      ],
      "target": "/1x/:category"
    }
  ],
  "url": "1x.com"
}
```
