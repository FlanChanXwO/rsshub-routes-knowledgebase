# BBC - News

## Coverage
`index-only`

## Route
- Namespace: `bbc`
- Namespace Name: `BBC`
- Route Path: `/:site?/:channel?`
- Route Name: `News`
- Example: `/bbc/world-asia`
- URL: `bbc.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `HenryQW, DIYgod, pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/bbc/index.ts')`

## Description
Provides a better reading experience (full text articles) over the official ones.

    Support major channels, refer to [BBC RSS feeds](https://www.bbc.co.uk/news/10628494). Eg, `business` for `https://feeds.bbci.co.uk/news/business/rss.xml`.

    -   Channel contains sub-directories, such as `https://feeds.bbci.co.uk/news/world/asia/rss.xml`, replace `/` with `-`, `/bbc/world-asia`.

## Parameters
- `site`: 语言，简体或繁体中文
- `channel`: channel, default to `top stories`


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Provides a better reading experience (full text articles) over the official ones.\n\n    Support major channels, refer to [BBC RSS feeds](https://www.bbc.co.uk/news/10628494). Eg, `business` for `https://feeds.bbci.co.uk/news/business/rss.xml`.\n\n    -   Channel contains sub-directories, such as `https://feeds.bbci.co.uk/news/world/asia/rss.xml`, replace `/` with `-`, `/bbc/world-asia`.",
  "example": "/bbc/world-asia",
  "location": "index.ts",
  "maintainers": [
    "HenryQW",
    "DIYgod",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/bbc/index.ts')",
  "name": "News",
  "parameters": {
    "channel": "channel, default to `top stories`",
    "site": "语言，简体或繁体中文"
  },
  "path": "/:site?/:channel?"
}
```
