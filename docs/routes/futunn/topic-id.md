# Futubull 富途牛牛 - 专题

## Coverage
`index-only`

## Route
- Namespace: `futunn`
- Namespace Name: `Futubull 富途牛牛`
- Route Path: `/topic/:id`
- Route Name: `专题`
- Example: `/futunn/topic/1267`
- URL: `news.futunn.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `kennyfong19931`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/futunn/topic.ts')`

## Description
_None_

## Parameters
- `id`: Topic ID, can be found in URL


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `news.futunn.com/news-topics/:id/*`
  - `news.futunn.com/:lang/news-topics/:id/*`
- `target`: `/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/futunn/topic/1267",
  "features": {
    "supportRadar": true
  },
  "location": "topic.ts",
  "maintainers": [
    "kennyfong19931"
  ],
  "module": "() => import('@/routes/futunn/topic.ts')",
  "name": "专题",
  "parameters": {
    "id": "Topic ID, can be found in URL"
  },
  "path": "/topic/:id",
  "radar": [
    {
      "source": [
        "news.futunn.com/news-topics/:id/*",
        "news.futunn.com/:lang/news-topics/:id/*"
      ],
      "target": "/topic/:id"
    }
  ]
}
```
