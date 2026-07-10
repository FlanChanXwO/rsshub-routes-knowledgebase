# JAVLibrary - Videos by star

## Coverage
`index-only`

## Route
- Namespace: `javlibrary`
- Namespace Name: `JAVLibrary`
- Route Path: `/javlibrary/star/:id/:language?/:mode?`
- Route Name: `Videos by star`
- Example: `/javlibrary/star/abbds/en`
- URL: `javlibrary.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `star.ts`
- Source Module: `_None_`

## Description
| videos with comments (by date) | everything (by date) |
| ------------------------------ | -------------------- |
| 1                              | 2                    |

::: tip
See [Ranking](https://www.javlibrary.com/en/star_mostfav.php) to view stars by ranks.

See [Directory](https://www.javlibrary.com/en/star_list.php) to view all stars.
:::

## Parameters
- `id`: Star id, can be found in URL
- `language`: Language, see below, Japanese by default, as `ja`
- `mode`: Mode, see below, videos with comments (by date) by default, as `1`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| videos with comments (by date) | everything (by date) |\n| ------------------------------ | -------------------- |\n| 1                              | 2                    |\n\n::: tip\nSee [Ranking](https://www.javlibrary.com/en/star_mostfav.php) to view stars by ranks.\n\nSee [Directory](https://www.javlibrary.com/en/star_list.php) to view all stars.\n:::",
  "example": "/javlibrary/star/abbds/en",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "star.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Videos by star",
  "parameters": {
    "id": "Star id, can be found in URL",
    "language": "Language, see below, Japanese by default, as `ja`",
    "mode": "Mode, see below, videos with comments (by date) by default, as `1`"
  },
  "path": "/star/:id/:language?/:mode?",
  "topFeeds": []
}
```
