# Furstar - 已经出售的角色列表

## Coverage
`index-only`

## Route
- Namespace: `furstar`
- Namespace Name: `Furstar`
- Route Path: `/furstar/archive/:lang?`
- Route Name: `已经出售的角色列表`
- Example: `/furstar/archive/cn`
- URL: `furstar.jp`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `NeverBehave`
- Source Location: `archive.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: 语言, 留空为jp, 支持cn, en


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
  - `furstar.jp/:lang/archive.php`
  - `furstar.jp/archive.php`
- `target`: `/archive/:lang`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/furstar/archive/cn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "archive.ts",
  "maintainers": [
    "NeverBehave"
  ],
  "name": "已经出售的角色列表",
  "parameters": {
    "lang": "语言, 留空为jp, 支持cn, en"
  },
  "path": "/archive/:lang?",
  "radar": [
    {
      "source": [
        "furstar.jp/:lang/archive.php",
        "furstar.jp/archive.php"
      ],
      "target": "/archive/:lang"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
