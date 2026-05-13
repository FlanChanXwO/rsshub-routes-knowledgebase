# Sensor Tower - Blog

## Coverage
`index-only`

## Route
- Namespace: `sensortower`
- Namespace Name: `Sensor Tower`
- Route Path: `/blog/:language?`
- Route Name: `Blog`
- Example: `/sensortower/blog`
- URL: `sensortower.com/blog`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/sensortower/blog.ts')`

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
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/sensortower/blog.ts')",
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
  "url": "sensortower.com/blog"
}
```
