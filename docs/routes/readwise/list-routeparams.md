# Readwise - Reader Document List

## Coverage
`index-only`

## Route
- Namespace: `readwise`
- Namespace Name: `Readwise`
- Route Path: `/list/:routeParams?`
- Route Name: `Reader Document List`
- Example: `/readwise/list/location=new&category=article`
- URL: `readwise.io`
- Language: `en`
- Categories: `reading`
- Maintainers: `xbot`
- Source Location: `list.ts`
- Source Module: `() => import('@/routes/readwise/list.ts')`

## Description
Specify options (in the format of query string) in parameter `routeParams` to filter documents.

| Parameter                  | Description                                                                            |   Values                                                                                    |  Default                             |
| -------------------------- | -------------------------------------------------------------------------------------- |   ----------------------------------------------------------------------------------------- |  ----------------------------------- |
| `location`               | The document's location.                                                               |   `new`/`later`/`shortlist`/`archive`/`feed`                                      |                                      |
| `category`               | The document's category.                                                               |   `article`/`email`/`rss`/`highlight`/`note`/`pdf`/`epub`/`tweet`/`video` |                                      |
| `updatedAfter`           | Fetch only documents updated after this date.                                          |   string (formatted as ISO 8601 date)                                                       ||
| `tag`                    | The document's tag, can be specified once or multiple times.                           |||
| `tagStrategy`            | If multiple tags are specified, should the documents match all of them or any of them. |   `any`/`all`                                                                           |  `any`                             |

Customise parameter values to fetch specific documents, for example:

```
https://rsshub.app/readwise/list/location=new&category=article
```

fetches articles in the Inbox.

```
https://rsshub.app/readwise/list/category=article&tag=shortlist&tag=AI&tagStrategy=all
```

fetches articles tagged both by `shortlist` and `AI`.

## Parameters
- `routeParams`: Parameter combinations, see the description above.


## Features
- `requireConfig`: [{"description": "Visit `https://readwise.io/access_token` to get your access token.", "name": "READWISE_ACCESS_TOKEN", "optional": false}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `read.readwise.io`
- `target`: `/list`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "Specify options (in the format of query string) in parameter `routeParams` to filter documents.\n\n| Parameter                  | Description                                                                            |   Values                                                                                    |  Default                             |\n| -------------------------- | -------------------------------------------------------------------------------------- |   ----------------------------------------------------------------------------------------- |  ----------------------------------- |\n| `location`               | The document's location.                                                               |   `new`/`later`/`shortlist`/`archive`/`feed`                                      |                                      |\n| `category`               | The document's category.                                                               |   `article`/`email`/`rss`/`highlight`/`note`/`pdf`/`epub`/`tweet`/`video` |                                      |\n| `updatedAfter`           | Fetch only documents updated after this date.                                          |   string (formatted as ISO 8601 date)                                                       ||\n| `tag`                    | The document's tag, can be specified once or multiple times.                           |||\n| `tagStrategy`            | If multiple tags are specified, should the documents match all of them or any of them. |   `any`/`all`                                                                           |  `any`                             |\n\nCustomise parameter values to fetch specific documents, for example:\n\n```\nhttps://rsshub.app/readwise/list/location=new&category=article\n```\n\nfetches articles in the Inbox.\n\n```\nhttps://rsshub.app/readwise/list/category=article&tag=shortlist&tag=AI&tagStrategy=all\n```\n\nfetches articles tagged both by `shortlist` and `AI`. ",
  "example": "/readwise/list/location=new&category=article",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Visit `https://readwise.io/access_token` to get your access token.",
        "name": "READWISE_ACCESS_TOKEN",
        "optional": false
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "list.ts",
  "maintainers": [
    "xbot"
  ],
  "module": "() => import('@/routes/readwise/list.ts')",
  "name": "Reader Document List",
  "parameters": {
    "routeParams": "Parameter combinations, see the description above."
  },
  "path": "/list/:routeParams?",
  "radar": [
    {
      "source": [
        "read.readwise.io"
      ],
      "target": "/list"
    }
  ]
}
```
