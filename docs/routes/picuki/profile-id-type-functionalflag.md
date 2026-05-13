# TikTok - User Profile - Picuki

## Coverage
`index-only`

## Route
- Namespace: `picuki`
- Namespace Name: `TikTok`
- Route Path: `/profile/:id/:type?/:functionalFlag?`
- Route Name: `User Profile - Picuki`
- Example: `/picuki/profile/linustech`
- URL: `tiktok.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `hoilc, Rongronggg9, devinmugen, NekoAria`
- Source Location: `profile.ts`
- Source Module: `() => import('@/routes/picuki/profile.ts')`

## Description
_None_

## Parameters
- `id`: Tiktok user id (without @)
- `type`: {"default": "profile", "description": "Type of profile page", "options": [{"label": "Profile Page", "value": "profile"}, {"label": "Story Page", "value": "story"}]}
- `functionalFlag`: {"default": "1", "description": "Functional flag for video embedding", "options": [{"label": "Off, only show video poster as an image", "value": "0"}, {"label": "On", "value": "1"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.picuki.com/profile/:id`
- `target`: `/profile/:id`
### Rule 2
- `source`:
  - `www.picuki.com/story/:id`
- `target`: `/profile/:id/story`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/picuki/profile/linustech",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "profile.ts",
  "maintainers": [
    "hoilc",
    "Rongronggg9",
    "devinmugen",
    "NekoAria"
  ],
  "module": "() => import('@/routes/picuki/profile.ts')",
  "name": "User Profile - Picuki",
  "parameters": {
    "functionalFlag": {
      "default": "1",
      "description": "Functional flag for video embedding",
      "options": [
        {
          "label": "Off, only show video poster as an image",
          "value": "0"
        },
        {
          "label": "On",
          "value": "1"
        }
      ]
    },
    "id": "Tiktok user id (without @)",
    "type": {
      "default": "profile",
      "description": "Type of profile page",
      "options": [
        {
          "label": "Profile Page",
          "value": "profile"
        },
        {
          "label": "Story Page",
          "value": "story"
        }
      ]
    }
  },
  "path": "/profile/:id/:type?/:functionalFlag?",
  "radar": [
    {
      "source": [
        "www.picuki.com/profile/:id"
      ],
      "target": "/profile/:id"
    },
    {
      "source": [
        "www.picuki.com/story/:id"
      ],
      "target": "/profile/:id/story"
    }
  ]
}
```
