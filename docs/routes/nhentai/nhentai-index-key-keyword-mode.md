# nhentai - Filter

## Coverage
`index-only`

## Route
- Namespace: `nhentai`
- Namespace Name: `nhentai`
- Route Path: `/nhentai/index/:key/:keyword/:mode?`
- Route Name: `Filter`
- Example: `/nhentai/index/language/chinese`
- URL: `nhentai.net`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `MegrezZhu, hoilc, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `key`: Filter term, can be: `parody`, `character`, `tag`, `artist`, `group`, `language` or `category`
- `keyword`: Filter value
- `mode`: mode, `simple` to only show cover, `detail` to show all pages, `torrent` to include Magnet URI, need login, refer to [Route-specific Configurations](https://docs.rsshub.app/deploy/config#route-specific-configurations), default to `simple`


## Features
- `requirePuppeteer`: false
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
  "categories": [
    "anime"
  ],
  "example": "/nhentai/index/language/chinese",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requirePuppeteer": false,
    "supportBT": true
  },
  "heat": 95,
  "location": "index.ts",
  "maintainers": [
    "MegrezZhu",
    "hoilc",
    "pseudoyu"
  ],
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
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "hentai - Powered by RSSHub",
      "errorAt": "2026-05-05T06:47:55.679Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "56236591640943616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nhentai.net/artist/doji-ro/",
      "title": "nhentai - artist - doji-ro",
      "type": "feed",
      "url": "rsshub://nhentai/index/artist/doji-ro"
    },
    {
      "description": "hentai - Powered by RSSHub",
      "errorAt": "2026-05-05T01:24:48.555Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "55635543915975680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nhentai.net/language/chinese/",
      "title": "nhentai - language - chinese",
      "type": "feed",
      "url": "rsshub://nhentai/index/language/chinese/detail"
    }
  ]
}
```
