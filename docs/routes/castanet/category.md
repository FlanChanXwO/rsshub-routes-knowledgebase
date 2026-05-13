# Castanet - News

## Coverage
`index-only`

## Route
- Namespace: `castanet`
- Namespace Name: `Castanet`
- Route Path: `/:category?`
- Route Name: `News`
- Example: `/castanet/Kelowna`
- URL: `www.castanet.net`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/castanet/news.ts')`

## Description
_None_

## Parameters
- `category`: {"default": "Recent Headlines", "description": "Category", "options": [{"label": "Top Headlines", "value": "Top Headlines"}, {"label": "Recent Headlines", "value": "Recent Headlines"}, {"label": "Kelowna", "value": "Kelowna"}, {"label": "West-Kelowna", "value": "West-Kelowna"}, {"label": "Peachland", "value": "Peachland"}, {"label": "Vernon", "value": "Vernon"}, {"label": "Salmon-Arm", "value": "Salmon-Arm"}, {"label": "Penticton", "value": "Penticton"}, {"label": "Oliver-Osoyoos", "value": "Oliver-Osoyoos"}, {"label": "Kamloops", "value": "Kamloops"}, {"label": "Nelson", "value": "Nelson"}, {"label": "BC", "value": "BC"}, {"label": "Canada", "value": "Canada"}, {"label": "World", "value": "World"}, {"label": "Business", "value": "Business"}, {"label": "Sports", "value": "Sports"}, {"label": "ShowBiz", "value": "ShowBiz"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.castanet.net/news/:category/`
- `target`: `/:category`
### Rule 2
- `source`:
  - `www.castanet.net/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/castanet/Kelowna",
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/castanet/news.ts')",
  "name": "News",
  "parameters": {
    "category": {
      "default": "Recent Headlines",
      "description": "Category",
      "options": [
        {
          "label": "Top Headlines",
          "value": "Top Headlines"
        },
        {
          "label": "Recent Headlines",
          "value": "Recent Headlines"
        },
        {
          "label": "Kelowna",
          "value": "Kelowna"
        },
        {
          "label": "West-Kelowna",
          "value": "West-Kelowna"
        },
        {
          "label": "Peachland",
          "value": "Peachland"
        },
        {
          "label": "Vernon",
          "value": "Vernon"
        },
        {
          "label": "Salmon-Arm",
          "value": "Salmon-Arm"
        },
        {
          "label": "Penticton",
          "value": "Penticton"
        },
        {
          "label": "Oliver-Osoyoos",
          "value": "Oliver-Osoyoos"
        },
        {
          "label": "Kamloops",
          "value": "Kamloops"
        },
        {
          "label": "Nelson",
          "value": "Nelson"
        },
        {
          "label": "BC",
          "value": "BC"
        },
        {
          "label": "Canada",
          "value": "Canada"
        },
        {
          "label": "World",
          "value": "World"
        },
        {
          "label": "Business",
          "value": "Business"
        },
        {
          "label": "Sports",
          "value": "Sports"
        },
        {
          "label": "ShowBiz",
          "value": "ShowBiz"
        }
      ]
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.castanet.net/news/:category/"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "www.castanet.net/"
      ],
      "target": "/"
    }
  ],
  "url": "www.castanet.net"
}
```
