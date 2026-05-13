# Science Magazine - Blogs

## Coverage
`index-only`

## Route
- Namespace: `science`
- Namespace Name: `Science Magazine`
- Route Path: `/blogs/:name?`
- Route Name: `Blogs`
- Example: `/science/blogs/pipeline`
- URL: `science.org`
- Language: `en`
- Categories: `journal`
- Maintainers: `TomHodson`
- Source Location: `blogs.ts`
- Source Module: `() => import('@/routes/science/blogs.ts')`

## Description
To subscribe to [IN THE PIPELINE by Derek Lowe’s](https://science.org/blogs/pipeline) or the [science editor's blog](https://science.org/blogs/editors-blog), use the name parameter `pipeline` or `editors-blog`.

## Parameters
- `name`: Short name for the blog, get this from the url. Defaults to pipeline


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `science.org/blogs/:name`
- `target`: `/blogs/:name`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "To subscribe to [IN THE PIPELINE by Derek Lowe’s](https://science.org/blogs/pipeline) or the [science editor's blog](https://science.org/blogs/editors-blog), use the name parameter `pipeline` or `editors-blog`.",
  "example": "/science/blogs/pipeline",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blogs.ts",
  "maintainers": [
    "TomHodson"
  ],
  "module": "() => import('@/routes/science/blogs.ts')",
  "name": "Blogs",
  "parameters": {
    "name": "Short name for the blog, get this from the url. Defaults to pipeline"
  },
  "path": "/blogs/:name?",
  "radar": [
    {
      "source": [
        "science.org/blogs/:name"
      ],
      "target": "/blogs/:name"
    }
  ]
}
```
