# BBC - Topics

## Coverage
`index-only`

## Route
- Namespace: `bbc`
- Namespace Name: `BBC`
- Route Path: `/topics/:topic`
- Route Name: `Topics`
- Example: `/bbc/topics/c77jz3md4rwt`
- URL: `bbc.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/bbc/topic.ts')`

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
  "location": "topic.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/bbc/topic.ts')",
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
  ]
}
```
