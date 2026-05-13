# DLsite - Ci-en Creators' Article

## Coverage
`index-only`

## Route
- Namespace: `dlsite`
- Namespace Name: `DLsite`
- Route Path: `/ci-en/:id/article`
- Route Name: `Ci-en Creators' Article`
- Example: `/dlsite/ci-en/7400/article`
- URL: `dlsite.com`
- Language: `ja`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `ci-en/article.ts`
- Source Module: `() => import('@/routes/dlsite/ci-en/article.ts')`

## Description
_None_

## Parameters
- `id`: Creator id, can be found in URL


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
  - `ci-en.dlsite.com/creator/:id/article/843558`
  - `ci-en.dlsite.com/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/dlsite/ci-en/7400/article",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ci-en/article.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/dlsite/ci-en/article.ts')",
  "name": "Ci-en Creators' Article",
  "parameters": {
    "id": "Creator id, can be found in URL"
  },
  "path": "/ci-en/:id/article",
  "radar": [
    {
      "source": [
        "ci-en.dlsite.com/creator/:id/article/843558",
        "ci-en.dlsite.com/"
      ]
    }
  ],
  "view": 0
}
```
