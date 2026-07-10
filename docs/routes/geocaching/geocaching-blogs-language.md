# Geocaching - Official Blogs

## Coverage
`index-only`

## Route
- Namespace: `geocaching`
- Namespace Name: `Geocaching`
- Route Path: `/geocaching/blogs/:language?`
- Route Name: `Official Blogs`
- Example: `/geocaching/blogs/en`
- URL: `geocaching.com/blog/`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `HankChow, Konano`
- Source Location: `blogs.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: {"default": "en", "description": "language", "options": [{"label": "English", "value": "en"}, {"label": "Deutsch", "value": "de"}, {"label": "Français", "value": "fr"}, {"label": "Español", "value": "es"}, {"label": "Nederlands", "value": "nl"}, {"label": "Čeština", "value": "cs"}, {"label": "Not Specified", "value": "all"}]}


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
  - `geocaching.com/blog/`
  - `geocaching.com/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/geocaching/blogs/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "blogs.ts",
  "maintainers": [
    "HankChow",
    "Konano"
  ],
  "name": "Official Blogs",
  "parameters": {
    "language": {
      "default": "en",
      "description": "language",
      "options": [
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Deutsch",
          "value": "de"
        },
        {
          "label": "Français",
          "value": "fr"
        },
        {
          "label": "Español",
          "value": "es"
        },
        {
          "label": "Nederlands",
          "value": "nl"
        },
        {
          "label": "Čeština",
          "value": "cs"
        },
        {
          "label": "Not Specified",
          "value": "all"
        }
      ]
    }
  },
  "path": "/blogs/:language?",
  "radar": [
    {
      "source": [
        "geocaching.com/blog/",
        "geocaching.com/"
      ]
    }
  ],
  "topFeeds": [],
  "url": "geocaching.com/blog/"
}
```
