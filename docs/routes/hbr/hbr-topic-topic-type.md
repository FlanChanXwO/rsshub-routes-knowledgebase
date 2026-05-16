# Harvard Business Review - Topic

## Coverage
`index-only`

## Route
- Namespace: `hbr`
- Namespace Name: `Harvard Business Review`
- Route Path: `/hbr/topic/:topic?/:type?`
- Route Name: `Topic`
- Example: `/hbr/topic/Leadership/Popular`
- URL: `hbr.org`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `topic.ts`
- Source Module: `_None_`

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
  "description": "| POPULAR | FROM THE STORE | FOR YOU |\n| ------- | -------------- | ------- |\n| Popular | From the Store | For You |\n\n::: tip\nClick here to view [All Topics](https://hbr.org/topics)\n:::",
  "example": "/hbr/topic/Leadership/Popular",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 78,
  "location": "topic.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "Leadership - HBR - Popular - Powered by RSSHub",
      "errorAt": "2025-03-06T20:21:02.722Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "87319836309791744",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hbr.org/topic/Leadership",
      "title": "Leadership - HBR - Popular",
      "type": "feed",
      "url": "rsshub://hbr/topic/Leadership/Popular"
    },
    {
      "description": "Leadership - HBR - Popular - Powered by RSSHub",
      "errorAt": "2025-03-06T17:56:40.711Z",
      "errorMessage": "[GET] \"https://hbr.org/topic/Leadership\": 504 Gateway Time-out\n",
      "id": "41359648684677137",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hbr.org/topic/Leadership",
      "title": "Leadership - HBR - Popular",
      "type": "feed",
      "url": "rsshub://hbr/topic"
    }
  ]
}
```
