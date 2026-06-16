# Nature Journal - Unknown

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/nature/news-and-comment/:journal?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `nature.com/latest-news`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `news-and-comment.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `nature.com/latest-news`
  - `nature.com/news`
  - `nature.com/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "heat": 51,
  "location": "news-and-comment.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "name": "Unknown",
  "path": "/news-and-comment/:journal?",
  "radar": [
    {
      "source": [
        "nature.com/latest-news",
        "nature.com/news",
        "nature.com/"
      ],
      "target": "/news"
    }
  ],
  "topFeeds": [
    {
      "description": "Read the latest News & Comment articles from Nature Microbiology - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "161567544875957248",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/nmicrobiol/news-and-comment",
      "title": "News & Comment | Nature Microbiology",
      "type": "feed",
      "url": "rsshub://nature/news-and-comment/nmicrobiol"
    },
    {
      "description": "Read the latest News & Comment articles from Nature Energy - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160596099235667968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/nenergy/news-and-comment",
      "title": "News & Comment | Nature Energy",
      "type": "feed",
      "url": "rsshub://nature/news-and-comment/nenergy"
    }
  ],
  "url": "nature.com/latest-news"
}
```
