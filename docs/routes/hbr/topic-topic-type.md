# Harvard Business Review - Topic

## Coverage
`index-only`

## Route
- Namespace: `hbr`
- Namespace Name: `Harvard Business Review`
- Route Path: `/topic/:topic?/:type?`
- Route Name: `Topic`
- Example: `/hbr/topic/Leadership/Popular`
- URL: `hbr.org`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/hbr/topic.ts')`

## Description
| POPULAR | FROM THE STORE | FOR YOU |
| ------- | -------------- | ------- |
| Popular | From the Store | For You |

::: tip
  Click here to view [All Topics](https://hbr.org/topics)
:::

## Parameters
- `topic`: Topic, can be found in URL, Leadership by default
- `type`: {"default": "Popular", "description": "Type, see below, Popular by default", "options": [{"label": "Popular", "value": "Popular"}, {"label": "From the Store", "value": "From the Store"}, {"label": "For You", "value": "For You"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `hbr.org/topic/:topic?`
  - `hbr.org/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| POPULAR | FROM THE STORE | FOR YOU |\n| ------- | -------------- | ------- |\n| Popular | From the Store | For You |\n\n::: tip\n  Click here to view [All Topics](https://hbr.org/topics)\n:::",
  "example": "/hbr/topic/Leadership/Popular",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topic.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/hbr/topic.ts')",
  "name": "Topic",
  "parameters": {
    "topic": "Topic, can be found in URL, Leadership by default",
    "type": {
      "default": "Popular",
      "description": "Type, see below, Popular by default",
      "options": [
        {
          "label": "Popular",
          "value": "Popular"
        },
        {
          "label": "From the Store",
          "value": "From the Store"
        },
        {
          "label": "For You",
          "value": "For You"
        }
      ]
    }
  },
  "path": "/topic/:topic?/:type?",
  "radar": [
    {
      "source": [
        "hbr.org/topic/:topic?",
        "hbr.org/"
      ]
    }
  ]
}
```
