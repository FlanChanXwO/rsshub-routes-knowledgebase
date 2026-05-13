# AG⓪RA - 零博客

## Coverage
`index-only`

## Route
- Namespace: `agora0`
- Namespace Name: `AG⓪RA`
- Route Path: `/:category?`
- Route Name: `零博客`
- Example: `/agora0/initium`
- URL: `agorahub.github.io`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/agora0/index.ts')`

## Description
| muitinⒾ | aidemnⒾ | srettaⓂ | qⓅ | sucoⓋ |
| ------- | ------- | -------- | -- | ----- |
| initium | inmedia | matters  | pq | vocus |

## Parameters
- `category`: 分类，见下表，默认为 initium，即端传媒


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
  - `agora0.gitlab.io/blog/:category`
  - `agora0.gitlab.io/`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| muitinⒾ | aidemnⒾ | srettaⓂ | qⓅ | sucoⓋ |\n| ------- | ------- | -------- | -- | ----- |\n| initium | inmedia | matters  | pq | vocus |",
  "example": "/agora0/initium",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/agora0/index.ts')",
  "name": "零博客",
  "parameters": {
    "category": "分类，见下表，默认为 initium，即端传媒"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "agora0.gitlab.io/blog/:category",
        "agora0.gitlab.io/"
      ],
      "target": "/:category"
    }
  ]
}
```
