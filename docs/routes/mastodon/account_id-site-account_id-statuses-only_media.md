# Mastodon - User timeline (by account ID)

## Coverage
`index-only`

## Route
- Namespace: `mastodon`
- Namespace Name: `Mastodon`
- Route Path: `/account_id/:site/:account_id/statuses/:only_media?`
- Route Name: `User timeline (by account ID)`
- Example: `/mastodon/account_id/mas.to/109300507275095341/statuses/false`
- URL: `mastodon.social`
- Language: `en`
- Categories: `social-media`
- Maintainers: `notofoe, pseudoyu`
- Source Location: `account-id.ts`
- Source Module: `() => import('@/routes/mastodon/account-id.ts')`

## Description
_None_

## Parameters
- `site`: instance address, only domain, no `http://` or `https://` protocol header
- `account_id`: account ID, you can get it from `https://INSTANCE/api/v1/accounts/lookup?acct=USERNAME` api
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
  "example": "/mastodon/account_id/mas.to/109300507275095341/statuses/false",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "account-id.ts",
  "maintainers": [
    "notofoe",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/mastodon/account-id.ts')",
  "name": "User timeline (by account ID)",
  "parameters": {
    "account_id": "account ID, you can get it from `https://INSTANCE/api/v1/accounts/lookup?acct=USERNAME` api",
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
    },
    "site": "instance address, only domain, no `http://` or `https://` protocol header"
  },
  "path": "/account_id/:site/:account_id/statuses/:only_media?",
  "view": 1
}
```
