# Vimeo - User Profile

## Coverage
`index-only`

## Route
- Namespace: `vimeo`
- Namespace Name: `Vimeo`
- Route Path: `/user/:username/:cat?`
- Route Name: `User Profile`
- Example: `/vimeo/user/filmsupply/picks`
- URL: `vimeo.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `MisteryMonster`
- Source Location: `usr-videos.ts`
- Source Module: `() => import('@/routes/vimeo/usr-videos.ts')`

## Description
::: tip Special category name attention
  Some of the categories contain slash like `3D/CG` , must change the slash `/` to the vertical bar`|`.
:::

## Parameters
- `username`: In this example [https://vimeo.com/filmsupply](https://vimeo.com/filmsupply)  is `filmsupply`
- `cat`: deafult for all latest videos, others categories in this example such as `Docmentary`, `Narrative`, `Drama`. Set `picks` for promote orders, just orderd like web page. When `picks` added, published date won't show up


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
    "social-media"
  ],
  "description": "::: tip Special category name attention\n  Some of the categories contain slash like `3D/CG` , must change the slash `/` to the vertical bar`|`.\n:::",
  "example": "/vimeo/user/filmsupply/picks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "usr-videos.ts",
  "maintainers": [
    "MisteryMonster"
  ],
  "module": "() => import('@/routes/vimeo/usr-videos.ts')",
  "name": "User Profile",
  "parameters": {
    "cat": "deafult for all latest videos, others categories in this example such as `Docmentary`, `Narrative`, `Drama`. Set `picks` for promote orders, just orderd like web page. When `picks` added, published date won't show up",
    "username": "In this example [https://vimeo.com/filmsupply](https://vimeo.com/filmsupply)  is `filmsupply`"
  },
  "path": "/user/:username/:cat?",
  "view": 3
}
```
