# AtCoder - Posts

## Coverage
`index-only`

## Route
- Namespace: `atcoder`
- Namespace Name: `AtCoder`
- Route Path: `/post/:language?/:keyword?`
- Route Name: `Posts`
- Example: `/atcoder/post`
- URL: `atcoder.jp`
- Language: `en`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `post.ts`
- Source Module: `() => import('@/routes/atcoder/post.ts')`

## Description
_None_

## Parameters
- `language`: Language, `jp` as Japanese or `en` as English, English by default
- `keyword`: Keyword


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/atcoder/post",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "post.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/atcoder/post.ts')",
  "name": "Posts",
  "parameters": {
    "keyword": "Keyword",
    "language": "Language, `jp` as Japanese or `en` as English, English by default"
  },
  "path": "/post/:language?/:keyword?"
}
```
