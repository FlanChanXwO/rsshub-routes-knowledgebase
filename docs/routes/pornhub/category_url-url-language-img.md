# PornHub - Video List

## Coverage
`index-only`

## Route
- Namespace: `pornhub`
- Namespace Name: `PornHub`
- Route Path: `/category_url/:url?/:language?/:img?`
- Route Name: `Video List`
- Example: `/pornhub/category_url/video%3Fc%3D15%26o%3Dmv%26t%3Dw%26cc%3Djp`
- URL: `pornhub.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `I2IMk, queensferryme`
- Source Location: `category-url.ts`
- Source Module: `() => import('@/routes/pornhub/category-url.ts')`

## Description
**`language`**

  Refer to [Pornhub F.A.Qs](https://help.pornhub.com/hc/en-us/articles/360044327034-How-do-I-change-the-language-), English by default. For example:

  -   `cn` (Chinese), for Pornhub in China [https://cn.pornhub.com](https://cn.pornhub.com)；

  -   `jp` (Japanese), for Pornhub in Japan [https://jp.pornhub.com](https://jp.pornhub.com) etc.

## Parameters
- `language`: language, see below. defaults to `www` (English)
- `url`: relative path after `pornhub.com/`, need to be URL encoded
- `img`: show images, set to `img=1` to enable


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
  "description": "**`language`**\n\n  Refer to [Pornhub F.A.Qs](https://help.pornhub.com/hc/en-us/articles/360044327034-How-do-I-change-the-language-), English by default. For example:\n\n  -   `cn` (Chinese), for Pornhub in China [https://cn.pornhub.com](https://cn.pornhub.com)；\n\n  -   `jp` (Japanese), for Pornhub in Japan [https://jp.pornhub.com](https://jp.pornhub.com) etc.",
  "example": "/pornhub/category_url/video%3Fc%3D15%26o%3Dmv%26t%3Dw%26cc%3Djp",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "category-url.ts",
  "maintainers": [
    "I2IMk",
    "queensferryme"
  ],
  "module": "() => import('@/routes/pornhub/category-url.ts')",
  "name": "Video List",
  "parameters": {
    "img": "show images, set to `img=1` to enable",
    "language": "language, see below. defaults to `www` (English)",
    "url": "relative path after `pornhub.com/`, need to be URL encoded"
  },
  "path": "/category_url/:url?/:language?/:img?"
}
```
