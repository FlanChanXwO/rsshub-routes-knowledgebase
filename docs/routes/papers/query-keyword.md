# Cool Papers - Topic

## Coverage
`index-only`

## Route
- Namespace: `papers`
- Namespace Name: `Cool Papers`
- Route Path: `/query/:keyword{.+}?`
- Route Name: `Topic`
- Example: `/papers/query/Detection`
- URL: `papers.cool`
- Language: `en`
- Categories: `journal`
- Maintainers: `Muyun99`
- Source Location: `query.ts`
- Source Module: `() => import('@/routes/papers/query.ts')`

## Description
::: tip
  If you subscibe to [arXiv Paper queryed by Detection](https://papers.cool/arxiv/search?highlight=1&query=Detection), where the URL is `https://papers.cool/arxiv/search?highlight=1&query=Detection`, extract the part `https://papers.cool/` to the end, and use it as the parameter to fill in. Therefore, the route will be [`/papers/query/Detection`](https://rsshub.app/papers/query/Detection).
:::

| Category                                              | id                  |
| ----------------------------------------------------- | ------------------- |
| arXiv Paper queryed by Detection                      | query/Detection     |
| arXiv Paper queryed by Segmentation                   | query/Segmentation  |

## Parameters
- `keyword`: Keyword to search for papers, e.g., Detection, Segmentation, etc.


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `title`: `arXiv Paper queryed by Keyword`
- `source`:
  - `papers.cool/arxiv/search?highlight=1&query=*&sort=0`
- `target`: `/papers/query/:keyword`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "::: tip\n  If you subscibe to [arXiv Paper queryed by Detection](https://papers.cool/arxiv/search?highlight=1&query=Detection), where the URL is `https://papers.cool/arxiv/search?highlight=1&query=Detection`, extract the part `https://papers.cool/` to the end, and use it as the parameter to fill in. Therefore, the route will be [`/papers/query/Detection`](https://rsshub.app/papers/query/Detection).\n:::\n\n| Category                                              | id                  |\n| ----------------------------------------------------- | ------------------- |\n| arXiv Paper queryed by Detection                      | query/Detection     |\n| arXiv Paper queryed by Segmentation                   | query/Segmentation  |\n  ",
  "example": "/papers/query/Detection",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": true
  },
  "location": "query.ts",
  "maintainers": [
    "Muyun99"
  ],
  "module": "() => import('@/routes/papers/query.ts')",
  "name": "Topic",
  "parameters": {
    "keyword": "Keyword to search for papers, e.g., Detection, Segmentation, etc."
  },
  "path": "/query/:keyword{.+}?",
  "radar": [
    {
      "source": [
        "papers.cool/arxiv/search?highlight=1&query=*&sort=0"
      ],
      "target": "/papers/query/:keyword",
      "title": "arXiv Paper queryed by Keyword"
    }
  ],
  "url": "papers.cool"
}
```
