# Google - Play Store Update

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/play/:id/:lang?`
- Route Name: `Play Store Update`
- Example: `/google/play/net.dinglisch.android.taskerm`
- URL: `www.google.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `surwall`
- Source Location: `play.ts`
- Source Module: `() => import('@/routes/google/play.ts')`

## Description
_None_

## Parameters
- `id`: Package id, can be found in url
- `lang`: {"default": "en-us", "description": "language", "options": [{"label": "English", "value": "en-us"}, {"label": "简体中文", "value": "zh-cn"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `play.google.com/store/apps/details?id=:id`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/google/play/net.dinglisch.android.taskerm",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "play.ts",
  "maintainers": [
    "surwall"
  ],
  "module": "() => import('@/routes/google/play.ts')",
  "name": "Play Store Update",
  "parameters": {
    "id": "Package id, can be found in url",
    "lang": {
      "default": "en-us",
      "description": "language",
      "options": [
        {
          "label": "English",
          "value": "en-us"
        },
        {
          "label": "简体中文",
          "value": "zh-cn"
        }
      ]
    }
  },
  "path": "/play/:id/:lang?",
  "radar": [
    {
      "source": [
        "play.google.com/store/apps/details?id=:id"
      ]
    }
  ]
}
```
