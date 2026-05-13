# Scientific American - Podcasts

## Coverage
`index-only`

## Route
- Namespace: `scientificamerican`
- Namespace Name: `Scientific American`
- Route Path: `/podcast/:id?`
- Route Name: `Podcasts`
- Example: `/scientificamerican/podcast`
- URL: `www.scientificamerican.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `podcast.ts`
- Source Module: `() => import('@/routes/scientificamerican/podcast.ts')`

## Description
::: tip
If you subscribe to [Science Quickly](https://www.scientificamerican.com/podcast/science-quickly/)，where the URL is `https://www.scientificamerican.com/podcast/science-quickly/`, extract the part `https://www.scientificamerican.com/podcast/` to the end, which is `science-quickly`, and use it as the parameter to fill in. Therefore, the route will be [`/scientificamerican/podcast/science-quickly`](https://rsshub.app/scientificamerican/podcast/science-quickly).
:::

| All | Science Quickly | Uncertain    |
| --- | --------------- | ------------ |
|     | science-quickly | science-talk |

## Parameters
- `id`: ID, see below


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.scientificamerican.com/podcasts/`
  - `www.scientificamerican.com/podcast/:id`
### Rule 2
- `title`: `Science Quickly`
- `source`:
  - `www.scientificamerican.com/podcast/science-quickly/`
- `target`: `/podcast/science-quickly`
### Rule 3
- `title`: `Uncertain`
- `source`:
  - `www.scientificamerican.com/podcast/science-talk/`
- `target`: `/podcast/science-talk`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nIf you subscribe to [Science Quickly](https://www.scientificamerican.com/podcast/science-quickly/)，where the URL is `https://www.scientificamerican.com/podcast/science-quickly/`, extract the part `https://www.scientificamerican.com/podcast/` to the end, which is `science-quickly`, and use it as the parameter to fill in. Therefore, the route will be [`/scientificamerican/podcast/science-quickly`](https://rsshub.app/scientificamerican/podcast/science-quickly).\n:::\n\n| All | Science Quickly | Uncertain    |\n| --- | --------------- | ------------ |\n|     | science-quickly | science-talk |\n",
  "example": "/scientificamerican/podcast",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "podcast.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/scientificamerican/podcast.ts')",
  "name": "Podcasts",
  "parameters": {
    "id": "ID, see below"
  },
  "path": "/podcast/:id?",
  "radar": [
    {
      "source": [
        "www.scientificamerican.com/podcasts/",
        "www.scientificamerican.com/podcast/:id"
      ]
    },
    {
      "source": [
        "www.scientificamerican.com/podcast/science-quickly/"
      ],
      "target": "/podcast/science-quickly",
      "title": "Science Quickly"
    },
    {
      "source": [
        "www.scientificamerican.com/podcast/science-talk/"
      ],
      "target": "/podcast/science-talk",
      "title": "Uncertain"
    }
  ],
  "url": "www.scientificamerican.com",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [Science Quickly](https://www.scientificamerican.com/podcast/science-quickly/)，网址为 `https://www.scientificamerican.com/podcast/science-quickly/`，请截取 `https://www.scientificamerican.com/podcast/` 到末尾 `/` 的部分 `science-quickly` 作为 `id` 参数填入，此时目标路由为 [`/scientificamerican/podcast/science-quickly`](https://rsshub.app/scientificamerican/podcast/science-quickly)。\n:::\n\n| 全部 | Science Quickly | Uncertain    |\n| ---- | --------------- | ------------ |\n|      | science-quickly | science-talk |\n",
    "example": "/scientificamerican/podcast",
    "maintainers": [
      "nczitzk"
    ],
    "name": "Podcasts",
    "parameters": {
      "id": "ID，见下表"
    },
    "path": "/podcast/:id?",
    "url": "www.scientificamerican.com"
  }
}
```
