# Obsidian - Publish

## Coverage
`index-only`

## Route
- Namespace: `obsidian`
- Namespace Name: `Obsidian`
- Route Path: `/publish/:id`
- Route Name: `Publish`
- Example: `/obsidian/publish/marshallontheroad`
- URL: `publish.obsidian.md/`
- Language: `en`
- Categories: `blog`
- Maintainers: `Xy2002`
- Source Location: `publish.ts`
- Source Module: `() => import('@/routes/obsidian/publish.ts')`

## Description
_None_

## Parameters
- `id`: 网站 id，由Publish持有者自定义


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
  - `publish.obsidian.md/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/obsidian/publish/marshallontheroad",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "publish.ts",
  "maintainers": [
    "Xy2002"
  ],
  "module": "() => import('@/routes/obsidian/publish.ts')",
  "name": "Publish",
  "parameters": {
    "id": "网站 id，由Publish持有者自定义"
  },
  "path": "/publish/:id",
  "radar": [
    {
      "source": [
        "publish.obsidian.md/"
      ]
    }
  ],
  "url": "publish.obsidian.md/"
}
```
