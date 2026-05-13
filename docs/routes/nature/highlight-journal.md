# Nature Journal - Research Highlight

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/highlight/:journal?`
- Route Name: `Research Highlight`
- Example: `/nature/highlight`
- URL: `nature.com`
- Language: `en`
- Categories: `journal`
- Maintainers: `None`
- Source Location: `highlight.ts`
- Source Module: `() => import('@/routes/nature/highlight.ts')`

## Description
::: warning
  Only some journals are supported.
:::

## Parameters
- `journal`: short name for a journal, `nature` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `nature.com/:journal/articles`
  - `nature.com/:journal`
  - `nature.com/`
- `target`: `/highlight/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "::: warning\n  Only some journals are supported.\n:::",
  "example": "/nature/highlight",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "location": "highlight.ts",
  "maintainers": [],
  "module": "() => import('@/routes/nature/highlight.ts')",
  "name": "Research Highlight",
  "parameters": {
    "journal": "short name for a journal, `nature` by default"
  },
  "path": "/highlight/:journal?",
  "radar": [
    {
      "source": [
        "nature.com/:journal/articles",
        "nature.com/:journal",
        "nature.com/"
      ],
      "target": "/highlight/:journal"
    }
  ]
}
```
