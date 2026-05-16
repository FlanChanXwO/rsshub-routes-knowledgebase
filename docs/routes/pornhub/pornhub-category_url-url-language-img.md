# PornHub - Video List

## Coverage
`index-only`

## Route
- Namespace: `pornhub`
- Namespace Name: `PornHub`
- Route Path: `/pornhub/category_url/:url?/:language?/:img?`
- Route Name: `Video List`
- Example: `/pornhub/category_url/video%3Fc%3D15%26o%3Dmv%26t%3Dw%26cc%3Djp`
- URL: `pornhub.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `I2IMk, queensferryme`
- Source Location: `category-url.ts`
- Source Module: `_None_`

## Description
**`language`**

Refer to [Pornhub F.A.Qs](https://help.pornhub.com/hc/en-us/articles/360044327034-How-do-I-change-the-language-), English by default. For example:

- `cn` (Chinese), for Pornhub in China <https://cn.pornhub.com>；

- `jp` (Japanese), for Pornhub in Japan <https://jp.pornhub.com> etc.

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
  "description": "**`language`**\n\nRefer to [Pornhub F.A.Qs](https://help.pornhub.com/hc/en-us/articles/360044327034-How-do-I-change-the-language-), English by default. For example:\n\n- `cn` (Chinese), for Pornhub in China <https://cn.pornhub.com>；\n\n- `jp` (Japanese), for Pornhub in Japan <https://jp.pornhub.com> etc.",
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
  "heat": 117,
  "location": "category-url.ts",
  "maintainers": [
    "I2IMk",
    "queensferryme"
  ],
  "name": "Video List",
  "parameters": {
    "img": "show images, set to `img=1` to enable",
    "language": "language, see below. defaults to `www` (English)",
    "url": "relative path after `pornhub.com/`, need to be URL encoded"
  },
  "path": "/category_url/:url?/:language?/:img?",
  "topFeeds": [
    {
      "description": "Anal Creampie: Free Teen Creampies Videos | Pornhub - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58588081077915648",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pornhub.com/video?c=15&o=mv&t=w&cc=jp",
      "title": "Anal Creampie: Free Teen Creampies Videos | Pornhub",
      "type": "feed",
      "url": "rsshub://pornhub/category_url/video%3Fc%3D15%26o%3Dmv%26t%3Dw%26cc%3Djp"
    },
    {
      "description": "Gay Asian Cocks In Hot Free Porn Videos And Sex Clips | Pornhub - Powered by RSSHub",
      "errorAt": "2026-05-14T22:06:53.705Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "184894860867500032",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pornhub.com/gay/video?c=48",
      "title": "Gay Asian Cocks In Hot Free Porn Videos And Sex Clips | Pornhub",
      "type": "feed",
      "url": "rsshub://pornhub/category_url/gay%2Fvideo%3Fc%3D48"
    }
  ]
}
```
