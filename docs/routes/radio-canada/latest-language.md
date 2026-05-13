# Radio-Canada.ca - Latest News

## Coverage
`index-only`

## Route
- Namespace: `radio-canada`
- Namespace Name: `Radio-Canada.ca`
- Route Path: `/latest/:language?`
- Route Name: `Latest News`
- Example: `/radio-canada/latest`
- URL: `ici.radio-canada.ca`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `latest.ts`
- Source Module: `() => import('@/routes/radio-canada/latest.ts')`

## Description
| Français | English | Español | 简体中文 | 繁體中文 | العربية | ਪੰਜਾਬੀ | Tagalog |
| -------- | ------- | ------- | -------- | -------- | ------- | --- | ------- |
| fr       | en      | es      | zh-hans  | zh-hant  | ar      | pa  | tl      |

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
  - `ici.radio-canada.ca/rci/:lang`
  - `ici.radio-canada.ca/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Français | English | Español | 简体中文 | 繁體中文 | العربية | ਪੰਜਾਬੀ | Tagalog |\n| -------- | ------- | ------- | -------- | -------- | ------- | --- | ------- |\n| fr       | en      | es      | zh-hans  | zh-hant  | ar      | pa  | tl      |",
  "example": "/radio-canada/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "latest.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/radio-canada/latest.ts')",
  "name": "Latest News",
  "parameters": {
    "language": "Language, see below, English by default"
  },
  "path": "/latest/:language?",
  "radar": [
    {
      "source": [
        "ici.radio-canada.ca/rci/:lang",
        "ici.radio-canada.ca/"
      ]
    }
  ]
}
```
