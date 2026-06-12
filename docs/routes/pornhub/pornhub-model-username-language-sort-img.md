# PornHub - Model

## Coverage
`index-only`

## Route
- Namespace: `pornhub`
- Namespace Name: `PornHub`
- Route Path: `/pornhub/model/:username/:language?/:sort?/:img?`
- Route Name: `Model`
- Example: `/pornhub/model/stacy-starando`
- URL: `pornhub.com`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `I2IMk, queensferryme`
- Source Location: `model.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: language, see below. defaults to www
- `username`: username, part of the url e.g. `pornhub.com/model/stacy-starando`
- `sort`: sorting method, see below. Defaults to mr (most recent)
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
### Rule 1
- `source`:
  - `www.pornhub.com/model/:username`
  - `www.pornhub.com/model/:username/*`
- `target`: `/model/:username`
### Rule 2
- `source`:
  - `de.pornhub.com/model/:username`
  - `de.pornhub.com/model/:username/*`
- `target`: `/model/:username/de`
### Rule 3
- `source`:
  - `fr.pornhub.com/model/:username`
  - `fr.pornhub.com/model/:username/*`
- `target`: `/model/:username/fr`
### Rule 4
- `source`:
  - `es.pornhub.com/model/:username`
  - `es.pornhub.com/model/:username/*`
- `target`: `/model/:username/es`
### Rule 5
- `source`:
  - `it.pornhub.com/model/:username`
  - `it.pornhub.com/model/:username/*`
- `target`: `/model/:username/it`
### Rule 6
- `source`:
  - `pt.pornhub.com/model/:username`
  - `pt.pornhub.com/model/:username/*`
- `target`: `/model/:username/pt`
### Rule 7
- `source`:
  - `pl.pornhub.com/model/:username`
  - `pl.pornhub.com/model/:username/*`
- `target`: `/model/:username/pl`
### Rule 8
- `source`:
  - `rt.pornhub.com/model/:username`
  - `rt.pornhub.com/model/:username/*`
- `target`: `/model/:username/rt`
### Rule 9
- `source`:
  - `jp.pornhub.com/model/:username`
  - `jp.pornhub.com/model/:username/*`
- `target`: `/model/:username/jp`
### Rule 10
- `source`:
  - `nl.pornhub.com/model/:username`
  - `nl.pornhub.com/model/:username/*`
- `target`: `/model/:username/nl`
### Rule 11
- `source`:
  - `cz.pornhub.com/model/:username`
  - `cz.pornhub.com/model/:username/*`
- `target`: `/model/:username/cz`
### Rule 12
- `source`:
  - `cn.pornhub.com/model/:username`
  - `cn.pornhub.com/model/:username/*`
- `target`: `/model/:username/cn`

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "example": "/pornhub/model/stacy-starando",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 25361,
  "location": "model.ts",
  "maintainers": [
    "I2IMk",
    "queensferryme"
  ],
  "name": "Model",
  "parameters": {
    "img": "show images, set to `img=1` to enable",
    "language": "language, see below. defaults to www",
    "sort": "sorting method, see below. Defaults to mr (most recent)",
    "username": "username, part of the url e.g. `pornhub.com/model/stacy-starando`"
  },
  "path": "/model/:username/:language?/:sort?/:img?",
  "radar": [
    {
      "source": [
        "www.pornhub.com/model/:username",
        "www.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username"
    },
    {
      "source": [
        "de.pornhub.com/model/:username",
        "de.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/de"
    },
    {
      "source": [
        "fr.pornhub.com/model/:username",
        "fr.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/fr"
    },
    {
      "source": [
        "es.pornhub.com/model/:username",
        "es.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/es"
    },
    {
      "source": [
        "it.pornhub.com/model/:username",
        "it.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/it"
    },
    {
      "source": [
        "pt.pornhub.com/model/:username",
        "pt.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/pt"
    },
    {
      "source": [
        "pl.pornhub.com/model/:username",
        "pl.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/pl"
    },
    {
      "source": [
        "rt.pornhub.com/model/:username",
        "rt.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/rt"
    },
    {
      "source": [
        "jp.pornhub.com/model/:username",
        "jp.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/jp"
    },
    {
      "source": [
        "nl.pornhub.com/model/:username",
        "nl.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/nl"
    },
    {
      "source": [
        "cz.pornhub.com/model/:username",
        "cz.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/cz"
    },
    {
      "source": [
        "cn.pornhub.com/model/:username",
        "cn.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/cn"
    }
  ],
  "topFeeds": [
    {
      "description": "About andmlove Hello, Welcome to my video. I like role-playing and all kinds of stockings and high heels.If you also like my video, please give me a like and I love you🧡 - Powered by RSSHub",
      "errorAt": "2025-12-15T02:15:05.090Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nFailed to fetch\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "58050428808145920",
      "image": "https://ei.phncdn.com/pics/users/0026/0220/9011/avatar95587065/(m=ewILGCjadOf)(mh=t2Ki4ZlWy64XJHQI)200x200.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.pornhub.com/model/andmlove/videos",
      "title": "andmlove",
      "type": "feed",
      "url": "rsshub://pornhub/model/andmlove"
    },
    {
      "description": "About Candy Love •♥•♥✨⚡𝓦𝓮𝓵𝓬𝓸𝓶𝓮 𝓽𝓸 𝓶𝔂 𝓹𝓻𝓸𝓯𝓲𝓵𝓮⚡✨ ♥•♥•                Hi, I'm Candy, and you know... I shoot cool videos. I think they're cool. I hope u like it. I try to post videos every Sunday and Thursday. Don't forget to subscribe :3                ⚡•*´¨`*•.¸¸.•*´¨`*•.¸¸.•*´¨`*•.¸¸.•*´¨`*•.¸¸.•⚡                - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59551678679863296",
      "image": "https://ei.phncdn.com/pics/users/723/631/591/avatar1583837616/(m=ewILGCjadOf)(mh=Q6WMtzphnpbtDqca)200x200.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.pornhub.com/model/candy-love/videos",
      "title": "Candy Love",
      "type": "feed",
      "url": "rsshub://pornhub/model/candy-love"
    }
  ],
  "view": 3
}
```
