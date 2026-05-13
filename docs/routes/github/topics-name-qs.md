# GitHub - Topics

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/topics/:name/:qs?`
- Route Name: `Topics`
- Example: `/github/topics/framework`
- URL: `github.com/topics`
- Language: `en`
- Categories: `programming`
- Maintainers: `queensferryme`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/github/topic.ts')`

## Description
| Parameter | Description      | Values                                                                                                                          |
| --------- | ---------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| `l`       | Language         | For instance `php`, which can be found in the URL of the corresponding [Topics page](https://github.com/topics/framework?l=php) |
| `o`       | Sorting Order    | `asc`, `desc`                                                                                                                   |
| `s`       | Sorting Criteria | `stars`, `forks`, `updated`                                                                                                     |

  For instance, the `/github/topics/framework/l=php&o=desc&s=stars` route will generate the RSS feed corresponding to this [page](https://github.com/topics/framework?l=php&o=desc&s=stars).

## Parameters
- `name`: Topic name, which can be found in the URL of the corresponding [Topics Page](https://github.com/topics/framework)
- `qs`: Query string, like `l=php&o=desc&s=stars`. Details listed as follows:


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
  - `github.com/topics`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| Parameter | Description      | Values                                                                                                                          |\n| --------- | ---------------- | ------------------------------------------------------------------------------------------------------------------------------- |\n| `l`       | Language         | For instance `php`, which can be found in the URL of the corresponding [Topics page](https://github.com/topics/framework?l=php) |\n| `o`       | Sorting Order    | `asc`, `desc`                                                                                                                   |\n| `s`       | Sorting Criteria | `stars`, `forks`, `updated`                                                                                                     |\n\n  For instance, the `/github/topics/framework/l=php&o=desc&s=stars` route will generate the RSS feed corresponding to this [page](https://github.com/topics/framework?l=php&o=desc&s=stars).",
  "example": "/github/topics/framework",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topic.ts",
  "maintainers": [
    "queensferryme"
  ],
  "module": "() => import('@/routes/github/topic.ts')",
  "name": "Topics",
  "parameters": {
    "name": "Topic name, which can be found in the URL of the corresponding [Topics Page](https://github.com/topics/framework)",
    "qs": "Query string, like `l=php&o=desc&s=stars`. Details listed as follows:"
  },
  "path": "/topics/:name/:qs?",
  "radar": [
    {
      "source": [
        "github.com/topics"
      ]
    }
  ],
  "url": "github.com/topics"
}
```
