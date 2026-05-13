# nhentai - Filter

## Coverage
`index-only`

## Route
- Namespace: `nhentai`
- Namespace Name: `nhentai`
- Route Path: `/index/:key/:keyword/:mode?`
- Route Name: `Filter`
- Example: `/nhentai/index/language/chinese`
- URL: `nhentai.net`
- Language: `en`
- Categories: `anime`
- Maintainers: `MegrezZhu, hoilc, pseudoyu, FlanChanXwO`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/nhentai/index.ts')`

## Description
_None_

## Parameters
- `key`: Filter term, can be: `parody`, `character`, `tag`, `artist`, `group`, `language` or `category`
- `keyword`: Filter value
- `mode`: mode, `simple` to only show cover, `detail` to show all pages, `torrent` to include Magnet URI, need login, refer to [Route-specific Configurations](https://docs.rsshub.app/deploy/config#route-specific-configurations), default to `simple`


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: true
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `nhentai.net/:key/:keyword`
- `target`: `/index/:key/:keyword`

## Raw JSON
```json
{
  "example": "/nhentai/index/language/chinese",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requirePuppeteer": true,
    "supportBT": true
  },
  "location": "index.ts",
  "maintainers": [
    "MegrezZhu",
    "hoilc",
    "pseudoyu",
    "FlanChanXwO"
  ],
  "module": "() => import('@/routes/nhentai/index.ts')",
  "name": "Filter",
  "parameters": {
    "key": "Filter term, can be: `parody`, `character`, `tag`, `artist`, `group`, `language` or `category`",
    "keyword": "Filter value",
    "mode": "mode, `simple` to only show cover, `detail` to show all pages, `torrent` to include Magnet URI, need login, refer to [Route-specific Configurations](https://docs.rsshub.app/deploy/config#route-specific-configurations), default to `simple`"
  },
  "path": "/index/:key/:keyword/:mode?",
  "radar": [
    {
      "source": [
        "nhentai.net/:key/:keyword"
      ],
      "target": "/index/:key/:keyword"
    }
  ]
}
```
