# GitHub - User Followers

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/user/followers/:user`
- Route Name: `User Followers`
- Example: `/github/user/followers/HenryQW`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `HenryQW`
- Source Location: `follower.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: GitHub username


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
  - `github.com/:user`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/user/followers/HenryQW",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 20,
  "location": "follower.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "User Followers",
  "parameters": {
    "user": "GitHub username"
  },
  "path": "/user/followers/:user",
  "radar": [
    {
      "source": [
        "github.com/:user"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "Shubxam's followers - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "132457284343183360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/Shubxam",
      "title": "Shubxam's followers",
      "type": "feed",
      "url": "rsshub://github/user/followers/Shubxam"
    },
    {
      "description": "yihong0618's followers - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86779650812562432",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/yihong0618",
      "title": "yihong0618's followers",
      "type": "feed",
      "url": "rsshub://github/user/followers/yihong0618"
    }
  ]
}
```
