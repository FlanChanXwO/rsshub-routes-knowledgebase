# 91porn - Hot Video Today

## Coverage
`index-only`

## Route
- Namespace: `91porn`
- Namespace Name: `91porn`
- Route Path: `/:lang?`
- Route Name: `Hot Video Today`
- Example: `/91porn`
- URL: `91porn.com/index.php`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/91porn/index.ts')`

## Description
| English | 简体中文 | 繁體中文 |
| ------- | -------- | -------- |
| en_US  | cn_CN   | zh_ZH   |

## Parameters
- `lang`: Language, see below, `en_US` by default


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
  - `91porn.com/index.php`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| English | 简体中文 | 繁體中文 |\n| ------- | -------- | -------- |\n| en_US  | cn_CN   | zh_ZH   |",
  "example": "/91porn",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/91porn/index.ts')",
  "name": "Hot Video Today",
  "parameters": {
    "lang": "Language, see below, `en_US` by default "
  },
  "path": "/:lang?",
  "radar": [
    {
      "source": [
        "91porn.com/index.php"
      ],
      "target": ""
    }
  ],
  "url": "91porn.com/index.php"
}
```
