# Instagram - User Profile / Hashtag - Private API

## Coverage
`index-only`

## Route
- Namespace: `instagram`
- Namespace Name: `Instagram`
- Route Path: `/:category/:key`
- Route Name: `User Profile / Hashtag - Private API`
- Example: `/instagram/user/stefaniejoosten`
- URL: `www.instagram.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `oppilate, DIYgod`
- Source Location: `private-api/index.ts`
- Source Module: `() => import('@/routes/instagram/private-api/index.ts')`

## Description
_None_

## Parameters
- `category`: {"default": "user", "description": "Feed category", "options": [{"label": "User", "value": "user"}, {"label": "Tags", "value": "tags"}]}
- `key`: Username / Hashtag name


## Features
- `requireConfig`: [{"description": "", "name": "IG_PROXY", "optional": true}, {"description": "Instagram username", "name": "IG_USERNAME"}, {"description": "Instagram password, due to [Instagram Private API](https://github.com/dilame/instagram-private-api) restrictions, you have to setup your credentials on the server. 2FA is not supported.", "name": "IG_PASSWORD"}]
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "example": "/instagram/user/stefaniejoosten",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "IG_PROXY",
        "optional": true
      },
      {
        "description": "Instagram username",
        "name": "IG_USERNAME"
      },
      {
        "description": "Instagram password, due to [Instagram Private API](https://github.com/dilame/instagram-private-api) restrictions, you have to setup your credentials on the server. 2FA is not supported.",
        "name": "IG_PASSWORD"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "private-api/index.ts",
  "maintainers": [
    "oppilate",
    "DIYgod"
  ],
  "module": "() => import('@/routes/instagram/private-api/index.ts')",
  "name": "User Profile / Hashtag - Private API",
  "parameters": {
    "category": {
      "default": "user",
      "description": "Feed category",
      "options": [
        {
          "label": "User",
          "value": "user"
        },
        {
          "label": "Tags",
          "value": "tags"
        }
      ]
    },
    "key": "Username / Hashtag name"
  },
  "path": "/:category/:key",
  "view": 1
}
```
