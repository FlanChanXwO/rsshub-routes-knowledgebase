# Sensor Tower - Blog

## Coverage
`index-only`

## Route
- Namespace: `sensortower`
- Namespace Name: `Sensor Tower`
- Route Path: `/sensortower/blog/:language?`
- Route Name: `Blog`
- Example: `/sensortower/blog`
- URL: `sensortower.com/blog`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
| English | Chinese | Japanese | Korean |
| ------- | ------- | -------- | ------ |
|         | zh-CN   | ja       | ko     |

## Parameters
- `language`: Language, see below, English by default


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
  - `sensortower.com/blog`
  - `sensortower.com/zh-CN/blog`
  - `sensortower.com/ja/blog`
  - `sensortower.com/ko/blog`
  - `sensortower.com/`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| English | Chinese | Japanese | Korean |\n| ------- | ------- | -------- | ------ |\n|         | zh-CN   | ja       | ko     |",
  "example": "/sensortower/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Blog",
  "parameters": {
    "language": "Language, see below, English by default"
  },
  "path": "/blog/:language?",
  "radar": [
    {
      "source": [
        "sensortower.com/blog",
        "sensortower.com/zh-CN/blog",
        "sensortower.com/ja/blog",
        "sensortower.com/ko/blog",
        "sensortower.com/"
      ],
      "target": "/blog"
    }
  ],
  "topFeeds": [
    {
      "description": "Sensor Tower - Blog - Powered by RSSHub",
      "errorAt": "2025-01-07T20:39:28.418Z",
      "errorMessage": "Cannot read properties of null (reading 'map')\n",
      "id": "59813822042329088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sensortower.com/blog",
      "title": "Sensor Tower - Blog",
      "type": "feed",
      "url": "rsshub://sensortower/blog"
    }
  ],
  "url": "sensortower.com/blog"
}
```
