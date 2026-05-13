# Radio France Internationale - Generic News

## Coverage
`index-only`

## Route
- Namespace: `rfi`
- Namespace Name: `Radio France Internationale`
- Route Path: `/:path{.+}?`
- Route Name: `Generic News`
- Example: `/rfi`
- URL: `rfi.fr`
- Language: `fr`
- Categories: `None`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/rfi/news.ts')`

## Description
::: tip
-   To subscribe to [English News](https://www.rfi.fr/en/), which URL is `https://www.rfi.fr/en`, you can get the route as [`/rfi/en`](https://rsshub.app/rfi/en).
-   To subscribe to [English Europe News](https://www.rfi.fr/en/europe/), which URL is `https://www.rfi.fr/en/europe`, you can get the route as [`/rfi/en/europe`](https://rsshub.app/rfi/en/europe).
-   To subscribe to topic [Paris Olympics 2024](https://www.rfi.fr/en/tag/paris-olympics-2024/), which URL is `https://www.rfi.fr/en/tag/paris-olympics-2024`, you can get the route as [`/rfi/en/tag/paris-olympics-2024`](https://rsshub.app/rfi/en/tag/paris-olympics-2024).
:::

::: warning
This route does not support podcasts, please use the Offical RSS feed instead.
:::

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `rfi.fr/*path`
- `target`: `/:path`

## Raw JSON
```json
{
  "description": "::: tip\n-   To subscribe to [English News](https://www.rfi.fr/en/), which URL is `https://www.rfi.fr/en`, you can get the route as [`/rfi/en`](https://rsshub.app/rfi/en).\n-   To subscribe to [English Europe News](https://www.rfi.fr/en/europe/), which URL is `https://www.rfi.fr/en/europe`, you can get the route as [`/rfi/en/europe`](https://rsshub.app/rfi/en/europe).\n-   To subscribe to topic [Paris Olympics 2024](https://www.rfi.fr/en/tag/paris-olympics-2024/), which URL is `https://www.rfi.fr/en/tag/paris-olympics-2024`, you can get the route as [`/rfi/en/tag/paris-olympics-2024`](https://rsshub.app/rfi/en/tag/paris-olympics-2024).\n:::\n\n::: warning\nThis route does not support podcasts, please use the Offical RSS feed instead.\n:::\n",
  "example": "/rfi",
  "location": "news.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/rfi/news.ts')",
  "name": "Generic News",
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "rfi.fr/*path"
      ],
      "target": "/:path"
    }
  ],
  "url": "rfi.fr"
}
```
