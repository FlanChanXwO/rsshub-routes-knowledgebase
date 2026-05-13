# Rawkuma - Manga

## Coverage
`index-only`

## Route
- Namespace: `rawkuma`
- Namespace Name: `Rawkuma`
- Route Path: `/manga/:id`
- Route Name: `Manga`
- Example: `/rawkuma/manga/tensei-shitara-dai-nana-ouji-dattanode-kimamani-majutsu-o-kiwamemasu`
- URL: `rawkuma.com`
- Language: `en`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `manga.tsx`
- Source Module: `() => import('@/routes/rawkuma/manga.tsx')`

## Description
_None_

## Parameters
- `id`: Manga ID, can be found in URL


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
  - `rawkuma.com/manga/:id`
  - `rawkuma.com/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/rawkuma/manga/tensei-shitara-dai-nana-ouji-dattanode-kimamani-majutsu-o-kiwamemasu",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "manga.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/rawkuma/manga.tsx')",
  "name": "Manga",
  "parameters": {
    "id": "Manga ID, can be found in URL"
  },
  "path": "/manga/:id",
  "radar": [
    {
      "source": [
        "rawkuma.com/manga/:id",
        "rawkuma.com/"
      ]
    }
  ]
}
```
