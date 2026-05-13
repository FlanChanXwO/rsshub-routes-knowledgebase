# BBC - Topics

## Coverage
`index-only`

## Route
- Namespace: `bbc`
- Namespace Name: `BBC`
- Route Path: `/bbc/topics/:topic`
- Route Name: `Topics`
- Example: `/bbc/topics/c77jz3md4rwt`
- URL: `bbc.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: The topic ID to fetch news for, can be found in the URL.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bbc.com/news/topics/:topic`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/bbc/topics/c77jz3md4rwt",
  "heat": 1,
  "location": "topic.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Topics",
  "parameters": {
    "topic": "The topic ID to fetch news for, can be found in the URL."
  },
  "path": "/topics/:topic",
  "radar": [
    {
      "source": [
        "www.bbc.com/news/topics/:topic"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "All the latest content about Sweden from the BBC. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "254443574820593664",
      "image": "https://www.bbc.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.bbc.com/news/topics/c77jz3md4rwt",
      "title": "Sweden - BBC News",
      "type": "feed",
      "url": "rsshub://bbc/topics/c77jz3md4rwt"
    }
  ]
}
```
