# Royal Society of Chemistry - Journal

## Coverage
`index-only`

## Route
- Namespace: `rsc`
- Namespace Name: `Royal Society of Chemistry`
- Route Path: `/journal/:id/:category?`
- Route Name: `Journal`
- Example: `/rsc/journal/ta`
- URL: `pubs.rsc.org`
- Language: `en`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `journal.tsx`
- Source Module: `() => import('@/routes/rsc/journal.tsx')`

## Description
::: tip
  All journals at [Current journals](https://pubs.rsc.org/en/journals)
:::

| All Recent Articles | Advance Articles |
| ------------------- | ---------------- |
| allrecentarticles   | advancearticles  |

## Parameters
- `id`: Journal id, can be found in URL
- `category`: Category, see below, All Recent Articles by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "::: tip\n  All journals at [Current journals](https://pubs.rsc.org/en/journals)\n:::\n\n| All Recent Articles | Advance Articles |\n| ------------------- | ---------------- |\n| allrecentarticles   | advancearticles  |",
  "example": "/rsc/journal/ta",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "journal.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/rsc/journal.tsx')",
  "name": "Journal",
  "parameters": {
    "category": "Category, see below, All Recent Articles by default",
    "id": "Journal id, can be found in URL"
  },
  "path": "/journal/:id/:category?"
}
```
