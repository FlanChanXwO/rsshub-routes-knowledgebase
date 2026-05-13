# nhentai - Advanced Search

## Coverage
`index-only`

## Route
- Namespace: `nhentai`
- Namespace Name: `nhentai`
- Route Path: `/search/:keyword/:mode?`
- Route Name: `Advanced Search`
- Example: `/nhentai/search/language%3Ajapanese+-scat+-yaoi+-guro+-"mosaic+censorship"`
- URL: `nhentai.net`
- Language: `en`
- Categories: `anime`
- Maintainers: `MegrezZhu, hoilc, pseudoyu, FlanChanXwO`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/nhentai/search.ts')`

## Description
_None_

## Parameters
- `keyword`: Keywords for search. You can copy the content after `q=` after searching on the original website, or you can enter it directly. See the [official website](https://nhentai.net/info/) for details
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
- `target`: `/:key/:keyword`

## Raw JSON
```json
{
  "example": "/nhentai/search/language%3Ajapanese+-scat+-yaoi+-guro+-\"mosaic+censorship\"",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requirePuppeteer": true,
    "supportBT": true
  },
  "location": "search.ts",
  "maintainers": [
    "MegrezZhu",
    "hoilc",
    "pseudoyu",
    "FlanChanXwO"
  ],
  "module": "() => import('@/routes/nhentai/search.ts')",
  "name": "Advanced Search",
  "parameters": {
    "keyword": "Keywords for search. You can copy the content after `q=` after searching on the original website, or you can enter it directly. See the [official website](https://nhentai.net/info/) for details",
    "mode": "mode, `simple` to only show cover, `detail` to show all pages, `torrent` to include Magnet URI, need login, refer to [Route-specific Configurations](https://docs.rsshub.app/deploy/config#route-specific-configurations), default to `simple`"
  },
  "path": "/search/:keyword/:mode?",
  "radar": [
    {
      "source": [
        "nhentai.net/:key/:keyword"
      ],
      "target": "/:key/:keyword"
    }
  ]
}
```
