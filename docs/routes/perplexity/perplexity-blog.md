# Perplexity - Blog

## Coverage
`index-only`

## Route
- Namespace: `perplexity`
- Namespace Name: `Perplexity`
- Route Path: `/perplexity/blog`
- Route Name: `Blog`
- Example: `/perplexity/blog`
- URL: `www.perplexity.ai`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `seeyangzhi`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
Perplexity Blog - Explore Perplexity's blog for articles, announcements, product updates, and tips to optimize your experience. Stay informed and make the most of Perplexity.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.perplexity.ai/hub`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "Perplexity Blog - Explore Perplexity's blog for articles, announcements, product updates, and tips to optimize your experience. Stay informed and make the most of Perplexity.",
  "example": "/perplexity/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "blog.ts",
  "maintainers": [
    "seeyangzhi"
  ],
  "name": "Blog",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "www.perplexity.ai/hub"
      ],
      "target": "/blog"
    }
  ],
  "topFeeds": [
    {
      "description": "Perplexity Blog - Powered by RSSHub",
      "errorAt": "2026-05-06T15:28:38.020Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "257997849784109056",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.perplexity.ai/hub",
      "title": "Perplexity Blog",
      "type": "feed",
      "url": "rsshub://perplexity/blog"
    }
  ],
  "url": "www.perplexity.ai",
  "view": 5
}
```
