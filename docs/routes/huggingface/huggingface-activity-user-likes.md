# Huggingface - User Likes Activity

## Coverage
`index-only`

## Route
- Namespace: `huggingface`
- Namespace Name: `Huggingface`
- Route Path: `/huggingface/activity/:user/likes`
- Route Name: `User Likes Activity`
- Example: `/huggingface/activity/dotwee/likes`
- URL: `huggingface.co`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `dotwee`
- Source Location: `user-likes.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: Hugging Face username


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
  - `huggingface.co/:user/activity/likes`
- `target`: `/activity/:user/likes`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/huggingface/activity/dotwee/likes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user-likes.ts",
  "maintainers": [
    "dotwee"
  ],
  "name": "User Likes Activity",
  "parameters": {
    "user": "Hugging Face username"
  },
  "path": "/activity/:user/likes",
  "radar": [
    {
      "source": [
        "huggingface.co/:user/activity/likes"
      ],
      "target": "/activity/:user/likes"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "huggingface.co"
}
```
