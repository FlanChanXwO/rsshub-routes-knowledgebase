# 91porn - Author

## Coverage
`index-only`

## Route
- Namespace: `91porn`
- Namespace Name: `91porn`
- Route Path: `/author/:uid/:lang?`
- Route Name: `Author`
- Example: `/91porn/author/2d6d2iWm4vVCwqujAZbSrKt2QJCbbaObv9HQ21Zo8wGJWudWBg`
- URL: `91porn.com/index.php`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `author.ts`
- Source Module: `() => import('@/routes/91porn/author.ts')`

## Description
_None_

## Parameters
- `uid`: Author ID, can be found in URL
- `lang`: Language, see above, `en_US` by default


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
  "example": "/91porn/author/2d6d2iWm4vVCwqujAZbSrKt2QJCbbaObv9HQ21Zo8wGJWudWBg",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "author.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/91porn/author.ts')",
  "name": "Author",
  "parameters": {
    "lang": "Language, see above, `en_US` by default ",
    "uid": "Author ID, can be found in URL"
  },
  "path": "/author/:uid/:lang?",
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
