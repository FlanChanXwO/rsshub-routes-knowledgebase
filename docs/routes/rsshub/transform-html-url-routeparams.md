# RSSHub - Transformation - HTML

## Coverage
`index-only`

## Route
- Namespace: `rsshub`
- Namespace Name: `RSSHub`
- Route Path: `/transform/html/:url/:routeParams`
- Route Name: `Transformation - HTML`
- Example: `/rsshub/transform/html/https%3A%2F%2Fwechat2rss.xlab.app%2Fposts%2Flist%2F/item=div%5Bclass%3D%27post%2Dcontent%27%5D%20p%20a`
- URL: `docs.rsshub.app`
- Language: `en`
- Categories: `other`
- Maintainers: `ttttmr, hyoban`
- Source Location: `transform/html.ts`
- Source Module: `() => import('@/routes/rsshub/transform/html.ts')`

## Description
Pass URL and transformation rules to convert HTML/JSON into RSS.

Specify options (in the format of query string) in parameter `routeParams` parameter to extract data from HTML.

| Key                 | Meaning                                                                                                       | Accepted Values | Default                  |
| ------------------- | ------------------------------------------------------------------------------------------------------------- | --------------- | ------------------------ |
| `title`           | The title of the RSS                                                                                          | `string`      | Extract from `<title>` |
| `item`            | The HTML elements as `item` using CSS selector                                                              | `string`      | html                     |
| `itemTitle`       | The HTML elements as `title` in `item` using CSS selector                                                 | `string`      | `item` element         |
| `itemTitleAttr`   | The attributes of `title` element as title                                                                  | `string`      | Element text             |
| `itemLink`        | The HTML elements as `link` in `item` using CSS selector                                                  | `string`      | `item` element         |
| `itemLinkAttr`    | The attributes of `link` element as link                                                                    | `string`      | `href`                 |
| `itemDesc`        | The HTML elements as `descrption` in `item` using CSS selector                                            | `string`      | `item` element         |
| `itemDescAttr`    | The attributes of `descrption` element as description                                                       | `string`      | Element html             |
| `itemPubDate`     | The HTML elements as `pubDate` in `item` using CSS selector                                               | `string`      | `item` element         |
| `itemPubDateAttr` | The attributes of `pubDate` element as pubDate                                                              | `string`      | Element html             |
| `itemContent`     | The HTML elements as `description` in `item` using CSS selector ( in `itemLink` page for full content ) | `string`      |                          |
| `encoding`        | The encoding of the HTML content                                                                              | `string`      | utf-8                    |

  Parameters parsing in the above example:

| Parameter     | Value                                     |
| ------------- | ----------------------------------------- |
| `url`         | `https://wechat2rss.xlab.app/posts/list/` |
| `routeParams` | `item=div[class='post-content'] p a`      |

  Parsing of `routeParams` parameter:

| Parameter | Value                           |
| --------- | ------------------------------- |
| `item`    | `div[class='post-content'] p a` |

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
  "description": "Pass URL and transformation rules to convert HTML/JSON into RSS.\n\nSpecify options (in the format of query string) in parameter `routeParams` parameter to extract data from HTML.\n\n| Key                 | Meaning                                                                                                       | Accepted Values | Default                  |\n| ------------------- | ------------------------------------------------------------------------------------------------------------- | --------------- | ------------------------ |\n| `title`           | The title of the RSS                                                                                          | `string`      | Extract from `<title>` |\n| `item`            | The HTML elements as `item` using CSS selector                                                              | `string`      | html                     |\n| `itemTitle`       | The HTML elements as `title` in `item` using CSS selector                                                 | `string`      | `item` element         |\n| `itemTitleAttr`   | The attributes of `title` element as title                                                                  | `string`      | Element text             |\n| `itemLink`        | The HTML elements as `link` in `item` using CSS selector                                                  | `string`      | `item` element         |\n| `itemLinkAttr`    | The attributes of `link` element as link                                                                    | `string`      | `href`                 |\n| `itemDesc`        | The HTML elements as `descrption` in `item` using CSS selector                                            | `string`      | `item` element         |\n| `itemDescAttr`    | The attributes of `descrption` element as description                                                       | `string`      | Element html             |\n| `itemPubDate`     | The HTML elements as `pubDate` in `item` using CSS selector                                               | `string`      | `item` element         |\n| `itemPubDateAttr` | The attributes of `pubDate` element as pubDate                                                              | `string`      | Element html             |\n| `itemContent`     | The HTML elements as `description` in `item` using CSS selector ( in `itemLink` page for full content ) | `string`      |                          |\n| `encoding`        | The encoding of the HTML content                                                                              | `string`      | utf-8                    |\n\n  Parameters parsing in the above example:\n\n| Parameter     | Value                                     |\n| ------------- | ----------------------------------------- |\n| `url`         | `https://wechat2rss.xlab.app/posts/list/` |\n| `routeParams` | `item=div[class='post-content'] p a`      |\n\n  Parsing of `routeParams` parameter:\n\n| Parameter | Value                           |\n| --------- | ------------------------------- |\n| `item`    | `div[class='post-content'] p a` |",
  "example": "/rsshub/transform/html/https%3A%2F%2Fwechat2rss.xlab.app%2Fposts%2Flist%2F/item=div%5Bclass%3D%27post%2Dcontent%27%5D%20p%20a",
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
  "location": "transform/html.ts",
  "maintainers": [
    "ttttmr",
    "hyoban"
  ],
  "module": "() => import('@/routes/rsshub/transform/html.ts')",
  "name": "Transformation - HTML",
  "parameters": {
    "routeParams": "Transformation rules, requires URL encode",
    "url": "`encodeURIComponent`ed URL address"
  },
  "path": "/transform/html/:url/:routeParams"
}
```
