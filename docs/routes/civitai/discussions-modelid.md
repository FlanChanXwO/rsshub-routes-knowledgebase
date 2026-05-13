# Civitai - Model discussions

## Coverage
`index-only`

## Route
- Namespace: `civitai`
- Namespace Name: `Civitai`
- Route Path: `/discussions/:modelId`
- Route Name: `Model discussions`
- Example: `/civitai/discussions/4384`
- URL: `civitai.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `DIYgod`
- Source Location: `discussions.ts`
- Source Module: `() => import('@/routes/civitai/discussions.ts')`

## Description
::: warning
Need to configure `CIVITAI_COOKIE` to obtain image information of NSFW models.
:::

## Parameters
- `modelId`: N


## Features
- `requireConfig`: [{"description": "", "name": "CIVITAI_COOKIE"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `civitai.com/models/:modelId`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "::: warning\nNeed to configure `CIVITAI_COOKIE` to obtain image information of NSFW models.\n:::",
  "example": "/civitai/discussions/4384",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "",
        "name": "CIVITAI_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "discussions.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/civitai/discussions.ts')",
  "name": "Model discussions",
  "parameters": {
    "modelId": "N"
  },
  "path": "/discussions/:modelId",
  "radar": [
    {
      "source": [
        "civitai.com/models/:modelId"
      ]
    }
  ]
}
```
