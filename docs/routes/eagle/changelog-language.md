# Eagle - Changelog

## Coverage
`index-only`

## Route
- Namespace: `eagle`
- Namespace Name: `Eagle`
- Route Path: `/changelog/:language?`
- Route Name: `Changelog`
- Example: `/eagle/changelog/en`
- URL: `cn.eagle.cool`
- Language: `zh-CN`
- Categories: `program-update`
- Maintainers: `tigercubden`
- Source Location: `changelog.ts`
- Source Module: `() => import('@/routes/eagle/changelog.ts')`

## Description
Language

| Simplified Chinese | Traditional Chinese | English |
| ------------------ | ------------------- | ------- |
| cn                 | tw                  | en      |

## Parameters
- `language`: Language, see list, default to be `cn`


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
    "program-update"
  ],
  "description": "Language\n\n| Simplified Chinese | Traditional Chinese | English |\n| ------------------ | ------------------- | ------- |\n| cn                 | tw                  | en      |",
  "example": "/eagle/changelog/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "changelog.ts",
  "maintainers": [
    "tigercubden"
  ],
  "module": "() => import('@/routes/eagle/changelog.ts')",
  "name": "Changelog",
  "parameters": {
    "language": "Language, see list, default to be `cn`"
  },
  "path": "/changelog/:language?"
}
```
