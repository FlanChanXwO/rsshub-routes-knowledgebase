# Voice of Mongolia - News

## Coverage
`index-only`

## Route
- Namespace: `vom`
- Namespace Name: `Voice of Mongolia`
- Route Path: `/featured/:lang?`
- Route Name: `News`
- Example: `/vom/featured`
- URL: `vom.mn`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `featured.ts`
- Source Module: `() => import('@/routes/vom/featured.ts')`

## Description
| English | 日本語 | Монгол | Русский | 简体中文 |
| ------- | ------ | ------ | ------- | -------- |
| en      | ja     | mn     | ru      | zh       |

## Parameters
- `lang`: Language, see the table below, `mn` by default


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
  - `vom.mn/:lang`
  - `vom.mn/`
- `target`: `/featured/:lang`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| English | 日本語 | Монгол | Русский | 简体中文 |\n| ------- | ------ | ------ | ------- | -------- |\n| en      | ja     | mn     | ru      | zh       |",
  "example": "/vom/featured",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "featured.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/vom/featured.ts')",
  "name": "News",
  "parameters": {
    "lang": "Language, see the table below, `mn` by default"
  },
  "path": "/featured/:lang?",
  "radar": [
    {
      "source": [
        "vom.mn/:lang",
        "vom.mn/"
      ],
      "target": "/featured/:lang"
    }
  ]
}
```
