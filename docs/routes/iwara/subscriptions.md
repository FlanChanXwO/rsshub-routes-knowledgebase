# iwara - User Subscriptions

## Coverage
`index-only`

## Route
- Namespace: `iwara`
- Namespace Name: `iwara`
- Route Path: `/subscriptions`
- Route Name: `User Subscriptions`
- Example: `/iwara/subscriptions`
- URL: `www.iwara.tv/`
- Language: `en`
- Categories: `anime`
- Maintainers: `FeCCC`
- Source Location: `subscriptions.ts`
- Source Module: `() => import('@/routes/iwara/subscriptions.ts')`

## Description
::: warning
  This route requires username and password, therefore it's only available when self-hosting, refer to the [Deploy Guide](https://docs.rsshub.app/deploy/config#route-specific-configurations) for route-specific configurations.
:::

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "", "name": "IWARA_USERNAME"}, {"description": "", "name": "IWARA_PASSWORD"}]
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.iwara.tv/subscriptions/videos`
  - `www.iwara.tv/subscriptions/images`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: warning\n  This route requires username and password, therefore it's only available when self-hosting, refer to the [Deploy Guide](https://docs.rsshub.app/deploy/config#route-specific-configurations) for route-specific configurations.\n:::",
  "example": "/iwara/subscriptions",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "",
        "name": "IWARA_USERNAME"
      },
      {
        "description": "",
        "name": "IWARA_PASSWORD"
      }
    ],
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "subscriptions.ts",
  "maintainers": [
    "FeCCC"
  ],
  "module": "() => import('@/routes/iwara/subscriptions.ts')",
  "name": "User Subscriptions",
  "parameters": {},
  "path": "/subscriptions",
  "radar": [
    {
      "source": [
        "www.iwara.tv/subscriptions/videos",
        "www.iwara.tv/subscriptions/images"
      ]
    }
  ],
  "url": "www.iwara.tv/"
}
```
