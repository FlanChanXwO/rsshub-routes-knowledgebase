# 禁漫天堂 - 专辑

## Coverage
`index-only`

## Route
- Namespace: `18comic`
- Namespace Name: `禁漫天堂`
- Route Path: `/album/:id`
- Route Name: `专辑`
- Example: `/18comic/album/292282`
- URL: `jmcomic.group/`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `album.ts`
- Source Module: `() => import('@/routes/18comic/album.ts')`

## Description
::: tip
  专辑 id 不包括 URL 中标题的部分。
:::

## Parameters
- `id`: 专辑 id，可在专辑页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `jmcomic.group/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: tip\n  专辑 id 不包括 URL 中标题的部分。\n:::",
  "example": "/18comic/album/292282",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "album.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/18comic/album.ts')",
  "name": "专辑",
  "parameters": {
    "id": "专辑 id，可在专辑页 URL 中找到"
  },
  "path": "/album/:id",
  "radar": [
    {
      "source": [
        "jmcomic.group/"
      ]
    }
  ],
  "url": "jmcomic.group/"
}
```
