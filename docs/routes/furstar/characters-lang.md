# Furstar - 最新售卖角色列表

## Coverage
`index-only`

## Route
- Namespace: `furstar`
- Namespace Name: `Furstar`
- Route Path: `/characters/:lang?`
- Route Name: `最新售卖角色列表`
- Example: `/furstar/characters/cn`
- URL: `furstar.jp`
- Language: `ja`
- Categories: `shopping`
- Maintainers: `NeverBehave`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/furstar/index.ts')`

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
  - `furstar.jp/:lang`
  - `furstar.jp/`
- `target`: `/characters/:lang`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/furstar/characters/cn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "NeverBehave"
  ],
  "module": "() => import('@/routes/furstar/index.ts')",
  "name": "最新售卖角色列表",
  "parameters": {
    "lang": "语言, 留空为jp, 支持cn, en"
  },
  "path": "/characters/:lang?",
  "radar": [
    {
      "source": [
        "furstar.jp/:lang",
        "furstar.jp/"
      ],
      "target": "/characters/:lang"
    }
  ]
}
```
