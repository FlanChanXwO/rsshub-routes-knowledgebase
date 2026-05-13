# Diario Frutícola - Filtro

## Coverage
`index-only`

## Route
- Namespace: `diariofruticola`
- Namespace Name: `Diario Frutícola`
- Route Path: `/filtro/:filter{.+}`
- Route Name: `Filtro`
- Example: `/diariofruticola/filtro/cerezas/71`
- URL: `diariofruticola.cl`
- Language: `es`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `filtro.ts`
- Source Module: `() => import('@/routes/diariofruticola/filtro.ts')`

## Description
::: tip
If you subscribe to [Cerezas](https://www.diariofruticola.cl/filtro/cerezas/71/)，where the URL is `https://www.diariofruticola.cl/filtro/cerezas/71/`, extract the part `https://diariofruticola.cl/filtro` to the end, which is `/`, and use it as the parameter to fill in. Therefore, the route will be [`/diariofruticola/filtro/cerezas/71`](https://rsshub.app/diariofruticola/filtro/cerezas/71).
:::

## Parameters
- `filter`: {"description": "Filter"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `diariofruticola.cl/filtro/:filter`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nIf you subscribe to [Cerezas](https://www.diariofruticola.cl/filtro/cerezas/71/)，where the URL is `https://www.diariofruticola.cl/filtro/cerezas/71/`, extract the part `https://diariofruticola.cl/filtro` to the end, which is `/`, and use it as the parameter to fill in. Therefore, the route will be [`/diariofruticola/filtro/cerezas/71`](https://rsshub.app/diariofruticola/filtro/cerezas/71).\n:::\n",
  "example": "/diariofruticola/filtro/cerezas/71",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "filtro.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/diariofruticola/filtro.ts')",
  "name": "Filtro",
  "parameters": {
    "filter": {
      "description": "Filter"
    }
  },
  "path": "/filtro/:filter{.+}",
  "radar": [
    {
      "source": [
        "diariofruticola.cl/filtro/:filter"
      ]
    }
  ],
  "url": "diariofruticola.cl",
  "view": 0
}
```
