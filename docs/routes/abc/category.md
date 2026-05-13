# ABC News (Australian Broadcasting Corporation) - Channel & Topic

## Coverage
`index-only`

## Route
- Namespace: `abc`
- Namespace Name: `ABC News (Australian Broadcasting Corporation)`
- Route Path: `/:category{.+}?`
- Route Name: `Channel & Topic`
- Example: `/wa`
- URL: `abc.net.au`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/abc/index.ts')`

## Description
::: tip
  All Topics in [Topic Library](https://abc.net.au/news/topics) are supported, you can fill in the field after `topic` in its URL, or fill in the `documentId`.

  For example, the URL for [Computer Science](https://www.abc.net.au/news/topic/computer-science) is `https://www.abc.net.au/news/topic/computer-science`, the `category` is `news/topic/computer-science`, and the `documentId` of the Topic is `2302`, so the route is [/abc/news/topic/computer-science](https://rsshub.app/abc/news/topic/computer-science) and [/abc/2302](https://rsshub.app/abc/2302).

  The supported channels are all listed in the table below. For other channels, please find the `documentId` in the source code of the channel page and fill it in as above.
:::

## Parameters
- `category`: Category, can be found in the URL, can also be filled in with the `documentId` in the source code of the page, `news/justin` as **Just In** by default


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `abc.net.au/:category*`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "\n::: tip\n  All Topics in [Topic Library](https://abc.net.au/news/topics) are supported, you can fill in the field after `topic` in its URL, or fill in the `documentId`.\n\n  For example, the URL for [Computer Science](https://www.abc.net.au/news/topic/computer-science) is `https://www.abc.net.au/news/topic/computer-science`, the `category` is `news/topic/computer-science`, and the `documentId` of the Topic is `2302`, so the route is [/abc/news/topic/computer-science](https://rsshub.app/abc/news/topic/computer-science) and [/abc/2302](https://rsshub.app/abc/2302).\n\n  The supported channels are all listed in the table below. For other channels, please find the `documentId` in the source code of the channel page and fill it in as above.\n:::",
  "example": "/wa",
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/abc/index.ts')",
  "name": "Channel & Topic",
  "parameters": {
    "category": "Category, can be found in the URL, can also be filled in with the `documentId` in the source code of the page, `news/justin` as **Just In** by default"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "abc.net.au/:category*"
      ],
      "target": "/:category"
    }
  ]
}
```
