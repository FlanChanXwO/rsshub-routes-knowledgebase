# Fansly - User Timeline

## Coverage
`index-only`

## Route
- Namespace: `fansly`
- Namespace Name: `Fansly`
- Route Path: `/user/:username`
- Route Name: `User Timeline`
- Example: `/fansly/user/AeriGoMoo`
- URL: `fansly.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `post.ts`
- Source Module: `() => import('@/routes/fansly/post.ts')`

## Description
_None_

## Parameters
- `username`: User ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `fansly.com/:username/posts`
  - `fansly.com/:username/media`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/fansly/user/AeriGoMoo",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "post.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/fansly/post.ts')",
  "name": "User Timeline",
  "parameters": {
    "username": "User ID"
  },
  "path": "/user/:username",
  "radar": [
    {
      "source": [
        "fansly.com/:username/posts",
        "fansly.com/:username/media"
      ]
    }
  ]
}
```
