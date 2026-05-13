# Mastodon - User timeline

## Coverage
`index-only`

## Route
- Namespace: `mastodon`
- Namespace Name: `Mastodon`
- Route Path: `/acct/:acct/statuses/:only_media?`
- Route Name: `User timeline`
- Example: `/mastodon/acct/Mastodon@mastodon.social/statuses`
- URL: `mastodon.social`
- Language: `en`
- Categories: `social-media`
- Maintainers: `notofoe`
- Source Location: `acct.ts`
- Source Module: `() => import('@/routes/mastodon/acct.ts')`

## Description
Started from Mastodon v4.0.0, the use of the `search` API in the route no longer requires a user token.
If the domain of your Webfinger account URI is the same as the API host of the instance (i.e., no delegation called in some other protocols), then no configuration is required and the route is available out of the box.
However, you can still specify these route-specific configurations if you need to override them.

## Parameters
- `acct`: Webfinger account URI, like `user@host`
- `only_media`: {"default": "false", "description": "whether only display media content, default to false, any value to true", "options": [{"label": "true", "value": "true"}, {"label": "false", "value": "false"}]}


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
  "description": "Started from Mastodon v4.0.0, the use of the `search` API in the route no longer requires a user token.\nIf the domain of your Webfinger account URI is the same as the API host of the instance (i.e., no delegation called in some other protocols), then no configuration is required and the route is available out of the box.\nHowever, you can still specify these route-specific configurations if you need to override them.",
  "example": "/mastodon/acct/Mastodon@mastodon.social/statuses",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "acct.ts",
  "maintainers": [
    "notofoe"
  ],
  "module": "() => import('@/routes/mastodon/acct.ts')",
  "name": "User timeline",
  "parameters": {
    "acct": "Webfinger account URI, like `user@host`",
    "only_media": {
      "default": "false",
      "description": "whether only display media content, default to false, any value to true",
      "options": [
        {
          "label": "true",
          "value": "true"
        },
        {
          "label": "false",
          "value": "false"
        }
      ]
    }
  },
  "path": "/acct/:acct/statuses/:only_media?",
  "view": 1
}
```
