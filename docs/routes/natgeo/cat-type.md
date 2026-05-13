# National Geographic - 分类

## Coverage
`index-only`

## Route
- Namespace: `natgeo`
- Namespace Name: `National Geographic`
- Route Path: `/:cat/:type?`
- Route Name: `分类`
- Example: `/natgeo/environment/article`
- URL: `nationalgeographic.com`
- Language: `en`
- Categories: `travel`
- Maintainers: `fengkx`
- Source Location: `natgeo.ts`
- Source Module: `() => import('@/routes/natgeo/natgeo.ts')`

## Description
_None_

## Parameters
- `cat`: 分类
- `type`: 类型, 例如`https://www.natgeomedia.com/environment/photo/`对应 `cat`, `type` 分别为 `environment`, `photo`


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
  - `natgeomedia.com/:cat/:type`
  - `natgeomedia.com/:cat/`
  - `natgeomedia.com/`
- `target`: `/:cat/:type?`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/natgeo/environment/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "natgeo.ts",
  "maintainers": [
    "fengkx"
  ],
  "module": "() => import('@/routes/natgeo/natgeo.ts')",
  "name": "分类",
  "parameters": {
    "cat": "分类",
    "type": "类型, 例如`https://www.natgeomedia.com/environment/photo/`对应 `cat`, `type` 分别为 `environment`, `photo`"
  },
  "path": "/:cat/:type?",
  "radar": [
    {
      "source": [
        "natgeomedia.com/:cat/:type",
        "natgeomedia.com/:cat/",
        "natgeomedia.com/"
      ],
      "target": "/:cat/:type?"
    }
  ]
}
```
