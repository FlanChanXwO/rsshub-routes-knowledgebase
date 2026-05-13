# Josh W Comeau - Articles and Tutorials

## Coverage
`index-only`

## Route
- Namespace: `joshwcomeau`
- Namespace Name: `Josh W Comeau`
- Route Path: `/latest/:category?`
- Route Name: `Articles and Tutorials`
- Example: `/joshwcomeau/latest/css`
- URL: `www.joshwcomeau.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `Rjnishant530`
- Source Location: `latest.ts`
- Source Module: `() => import('@/routes/joshwcomeau/latest.ts')`

## Description
_None_

## Parameters
- `category`: {"description": "Category", "options": [{"label": "CSS", "value": "css"}, {"label": "React", "value": "react"}, {"label": "Animation", "value": "animation"}, {"label": "JavaScript", "value": "javascript"}, {"label": "Career", "value": "career"}, {"label": "Blog", "value": "blog"}]}


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
  - `joshwcomeau.com/`
- `target`: `/latest`
### Rule 2
- `source`:
  - `joshwcomeau.com/:category`
- `target`: `/latest/:category`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/joshwcomeau/latest/css",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "latest.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/joshwcomeau/latest.ts')",
  "name": "Articles and Tutorials",
  "parameters": {
    "category": {
      "description": "Category",
      "options": [
        {
          "label": "CSS",
          "value": "css"
        },
        {
          "label": "React",
          "value": "react"
        },
        {
          "label": "Animation",
          "value": "animation"
        },
        {
          "label": "JavaScript",
          "value": "javascript"
        },
        {
          "label": "Career",
          "value": "career"
        },
        {
          "label": "Blog",
          "value": "blog"
        }
      ]
    }
  },
  "path": "/latest/:category?",
  "radar": [
    {
      "source": [
        "joshwcomeau.com/"
      ],
      "target": "/latest"
    },
    {
      "source": [
        "joshwcomeau.com/:category"
      ],
      "target": "/latest/:category"
    }
  ]
}
```
