# World Health Organization | WHO - Speeches

## Coverage
`index-only`

## Route
- Namespace: `who`
- Namespace Name: `World Health Organization | WHO`
- Route Path: `/speeches/:language?`
- Route Name: `Speeches`
- Example: `/who/speeches`
- URL: `who.int/director-general/speeches`
- Language: `en`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `speeches.ts`
- Source Module: `() => import('@/routes/who/speeches.ts')`

## Description
Language

| English | العربية | 中文 | Français | Русский | Español | Português |
| ------- | ------- | ---- | -------- | ------- | ------- | --------- |
| en      | ar      | zh   | fr       | ru      | es      | pt        |

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
  - `who.int/director-general/speeches`
- `target`: `/speeches`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Language\n\n| English | العربية | 中文 | Français | Русский | Español | Português |\n| ------- | ------- | ---- | -------- | ------- | ------- | --------- |\n| en      | ar      | zh   | fr       | ru      | es      | pt        |",
  "example": "/who/speeches",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "speeches.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/who/speeches.ts')",
  "name": "Speeches",
  "parameters": {
    "language": "Language, see below, English by default"
  },
  "path": "/speeches/:language?",
  "radar": [
    {
      "source": [
        "who.int/director-general/speeches"
      ],
      "target": "/speeches"
    }
  ],
  "url": "who.int/director-general/speeches"
}
```
