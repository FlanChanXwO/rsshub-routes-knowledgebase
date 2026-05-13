# iwara - User Subscriptions

## Coverage
`index-only`

## Route
- Namespace: `iwara`
- Namespace Name: `iwara`
- Route Path: `/iwara/subscriptions`
- Route Name: `User Subscriptions`
- Example: `/iwara/subscriptions`
- URL: `www.iwara.tv/`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `FeCCC`
- Source Location: `subscriptions.ts`
- Source Module: `_None_`

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
  "description": "::: warning\nThis route requires username and password, therefore it's only available when self-hosting, refer to the [Deploy Guide](https://docs.rsshub.app/deploy/config#route-specific-configurations) for route-specific configurations.\n:::",
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
  "heat": 16,
  "location": "subscriptions.ts",
  "maintainers": [
    "FeCCC"
  ],
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
  "topFeeds": [
    {
      "description": "Iwara Subscription - Powered by RSSHub",
      "errorAt": "2025-02-08T17:50:37.346Z",
      "errorMessage": "Iwara subscription RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/config#route-specific-configurations\">relevant config</a>\n",
      "id": "106240479887734784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.iwara.tv/",
      "title": "Iwara Subscription",
      "type": "feed",
      "url": "rsshub://iwara/subscriptions"
    }
  ],
  "url": "www.iwara.tv/"
}
```
