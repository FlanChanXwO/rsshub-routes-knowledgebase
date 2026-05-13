# The Verge - Category

## Coverage
`index-only`

## Route
- Namespace: `theverge`
- Namespace Name: `The Verge`
- Route Path: `/:hub?`
- Route Name: `Category`
- Example: `/theverge`
- URL: `theverge.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `HenryQW, vbali`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/theverge/index.ts')`

## Description
| Hub         | Hub name            |
| ----------- | ------------------- |
|             | All Posts           |
| android     | Android             |
| apple       | Apple               |
| apps        | Apps & Software     |
| blackberry  | BlackBerry          |
| culture     | Culture             |
| gaming      | Gaming              |
| hd          | HD & Home           |
| microsoft   | Microsoft           |
| photography | Photography & Video |
| policy      | Policy & Law        |
| web         | Web & Social        |

  Provides a better reading experience (full text articles) over the official one.

## Parameters
- `hub`: Hub, see below, All Posts by default


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
  - `theverge.com/:hub`
  - `theverge.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Hub         | Hub name            |\n| ----------- | ------------------- |\n|             | All Posts           |\n| android     | Android             |\n| apple       | Apple               |\n| apps        | Apps & Software     |\n| blackberry  | BlackBerry          |\n| culture     | Culture             |\n| gaming      | Gaming              |\n| hd          | HD & Home           |\n| microsoft   | Microsoft           |\n| photography | Photography & Video |\n| policy      | Policy & Law        |\n| web         | Web & Social        |\n\n  Provides a better reading experience (full text articles) over the official one.",
  "example": "/theverge",
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
    "HenryQW",
    "vbali"
  ],
  "module": "() => import('@/routes/theverge/index.ts')",
  "name": "Category",
  "parameters": {
    "hub": "Hub, see below, All Posts by default"
  },
  "path": "/:hub?",
  "radar": [
    {
      "source": [
        "theverge.com/:hub",
        "theverge.com/"
      ]
    }
  ]
}
```
