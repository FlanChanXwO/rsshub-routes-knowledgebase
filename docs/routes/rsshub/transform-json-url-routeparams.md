# RSSHub - Transformation - JSON

## Coverage
`index-only`

## Route
- Namespace: `rsshub`
- Namespace Name: `RSSHub`
- Route Path: `/transform/json/:url/:routeParams`
- Route Name: `Transformation - JSON`
- Example: `/rsshub/transform/json/https%3A%2F%2Fapi.github.com%2Frepos%2Fginuerzh%2Fgost%2Freleases/title=Gost%20releases&itemTitle=tag_name&itemLink=html_url&itemDesc=body`
- URL: `docs.rsshub.app`
- Language: `en`
- Categories: `other`
- Maintainers: `ttttmr`
- Source Location: `transform/json.ts`
- Source Module: `() => import('@/routes/rsshub/transform/json.ts')`

## Description
Specify options (in the format of query string) in parameter `routeParams` parameter to extract data from JSON.

| Key                | Meaning                                      | Accepted Values   | Default                                    |
| ------------------ | -------------------------------------------- | ----------------- | ------------------------------------------ |
| `title`          | The title of the RSS                         | `string`        | Extracted from home page of current domain |
| `item`           | The JSON Path as `item` element            | `string`        | Entire JSON response                       |
| `itemTitle`      | The JSON Path as `title` in `item`       | `string`        | None                                       |
| `itemLink`       | The JSON Path as `link` in `item`        | `string`        | None                                       |
| `itemLinkPrefix` | Optional Prefix for `itemLink` value       | `string`        | None                                       |
| `itemDesc`       | The JSON Path as `description` in `item` | `string`        | None                                       |
| `itemPubDate`    | The JSON Path as `pubDate` in `item`     | `string`        | None                                       |

::: tip
JSON Path only supports format like `a.b.c`. if you need to access arrays, like `a[0].b`, you can write it as `a.0.b`.
:::

  Parameters parsing in the above example:

| Parameter     | Value                                                                    |
| ------------- | ------------------------------------------------------------------------ |
| `url`         | `https://api.github.com/repos/ginuerzh/gost/releases`                    |
| `routeParams` | `title=Gost releases&itemTitle=tag_name&itemLink=html_url&itemDesc=body` |

  Parsing of `routeParams` parameter:

| Parameter   | Value           |
| ----------- | --------------- |
| `title`     | `Gost releases` |
| `itemTitle` | `tag_name`      |
| `itemLink`  | `html_url`      |
| `itemDesc`  | `body`          |

## Parameters
- `url`: `encodeURIComponent`ed URL address
- `routeParams`: Transformation rules, requires URL encode


## Features
- `requireConfig`: [{"description": "", "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Specify options (in the format of query string) in parameter `routeParams` parameter to extract data from JSON.\n\n| Key                | Meaning                                      | Accepted Values   | Default                                    |\n| ------------------ | -------------------------------------------- | ----------------- | ------------------------------------------ |\n| `title`          | The title of the RSS                         | `string`        | Extracted from home page of current domain |\n| `item`           | The JSON Path as `item` element            | `string`        | Entire JSON response                       |\n| `itemTitle`      | The JSON Path as `title` in `item`       | `string`        | None                                       |\n| `itemLink`       | The JSON Path as `link` in `item`        | `string`        | None                                       |\n| `itemLinkPrefix` | Optional Prefix for `itemLink` value       | `string`        | None                                       |\n| `itemDesc`       | The JSON Path as `description` in `item` | `string`        | None                                       |\n| `itemPubDate`    | The JSON Path as `pubDate` in `item`     | `string`        | None                                       |\n\n::: tip\nJSON Path only supports format like `a.b.c`. if you need to access arrays, like `a[0].b`, you can write it as `a.0.b`.\n:::\n\n  Parameters parsing in the above example:\n\n| Parameter     | Value                                                                    |\n| ------------- | ------------------------------------------------------------------------ |\n| `url`         | `https://api.github.com/repos/ginuerzh/gost/releases`                    |\n| `routeParams` | `title=Gost releases&itemTitle=tag_name&itemLink=html_url&itemDesc=body` |\n\n  Parsing of `routeParams` parameter:\n\n| Parameter   | Value           |\n| ----------- | --------------- |\n| `title`     | `Gost releases` |\n| `itemTitle` | `tag_name`      |\n| `itemLink`  | `html_url`      |\n| `itemDesc`  | `body`          |",
  "example": "/rsshub/transform/json/https%3A%2F%2Fapi.github.com%2Frepos%2Fginuerzh%2Fgost%2Freleases/title=Gost%20releases&itemTitle=tag_name&itemLink=html_url&itemDesc=body",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "transform/json.ts",
  "maintainers": [
    "ttttmr"
  ],
  "module": "() => import('@/routes/rsshub/transform/json.ts')",
  "name": "Transformation - JSON",
  "parameters": {
    "routeParams": "Transformation rules, requires URL encode",
    "url": "`encodeURIComponent`ed URL address"
  },
  "path": "/transform/json/:url/:routeParams"
}
```
