# Ktown4u - Get the products on sale

## Coverage
`index-only`

## Route
- Namespace: `ktown4u`
- Namespace Name: `Ktown4u`
- Route Path: `/artistBrandlist/:grpNo/:grpNo2?`
- Route Name: `Get the products on sale`
- Example: `/ktown4u/artistBrandlist/234590/1723449`
- URL: `ktown4u.com`
- Language: `en`
- Categories: `shopping`
- Maintainers: `JamesWDGu`
- Source Location: `artist-brandlist.ts`
- Source Module: `() => import('@/routes/ktown4u/artist-brandlist.ts')`

## Description
_None_

## Parameters
- `grpNo`: artist id (Get in url)
- `grpNo2`: product category id (Get in url), empty for all categories


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
- `target`: `/artistBrandlist/:grpNo/:grpNo2`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/ktown4u/artistBrandlist/234590/1723449",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "artist-brandlist.ts",
  "maintainers": [
    "JamesWDGu"
  ],
  "module": "() => import('@/routes/ktown4u/artist-brandlist.ts')",
  "name": "Get the products on sale",
  "parameters": {
    "grpNo": "artist id (Get in url)",
    "grpNo2": "product category id (Get in url), empty for all categories"
  },
  "path": "/artistBrandlist/:grpNo/:grpNo2?",
  "radar": [
    {
      "source": [],
      "target": "/artistBrandlist/:grpNo/:grpNo2"
    }
  ]
}
```
