# Huggingface - Group Models

## Coverage
`index-only`

## Route
- Namespace: `huggingface`
- Namespace Name: `Huggingface`
- Route Path: `/models/:group`
- Route Name: `Group Models`
- Example: `/huggingface/models/deepseek-ai`
- URL: `huggingface.co`
- Language: `en`
- Categories: `programming`
- Maintainers: `WuNein`
- Source Location: `models.ts`
- Source Module: `() => import('@/routes/huggingface/models.ts')`

## Description
_None_

## Parameters
- `group`: The organization or user group name


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
  - `huggingface.co/:group/models`
- `target`: `/models/:group`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/huggingface/models/deepseek-ai",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "models.ts",
  "maintainers": [
    "WuNein"
  ],
  "module": "() => import('@/routes/huggingface/models.ts')",
  "name": "Group Models",
  "parameters": {
    "group": "The organization or user group name"
  },
  "path": "/models/:group",
  "radar": [
    {
      "source": [
        "huggingface.co/:group/models"
      ],
      "target": "/models/:group"
    }
  ],
  "url": "huggingface.co"
}
```
