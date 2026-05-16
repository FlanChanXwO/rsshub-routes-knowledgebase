# KPMG - Insights

## Coverage
`index-only`

## Route
- Namespace: `kpmg`
- Namespace Name: `KPMG`
- Route Path: `/kpmg/insights/:lang?`
- Route Name: `Insights`
- Example: `/kpmg/insights`
- URL: `kpmg.com/xx/en/home/insights.html`
- Language: `_None_`
- Categories: `other`
- Maintainers: `LogicJake`
- Source Location: `insights.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: Language, either `en` or `zh`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `kpmg.com/xx/en/home/insights.html`
- `target`: `/insights/en`
### Rule 2
- `source`:
  - `kpmg.com/cn/zh/home/insights.html`
- `target`: `/insights/zh`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/kpmg/insights",
  "heat": 17,
  "location": "insights.tsx",
  "maintainers": [
    "LogicJake"
  ],
  "name": "Insights",
  "parameters": {
    "lang": "Language, either `en` or `zh`"
  },
  "path": "/insights/:lang?",
  "radar": [
    {
      "source": [
        "kpmg.com/xx/en/home/insights.html"
      ],
      "target": "/insights/en"
    },
    {
      "source": [
        "kpmg.com/cn/zh/home/insights.html"
      ],
      "target": "/insights/zh"
    }
  ],
  "topFeeds": [
    {
      "description": "KPMG Insights - Powered by RSSHub",
      "errorAt": "2026-04-11T12:51:46.487Z",
      "errorMessage": "[GET] \"https://kpmg.com/xx/en/home/insights/2024/08/european-commission-faqs-csrd-esrs.html\": 404 Not Found\n",
      "id": "67011938801010691",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://kpmg.com/xx/en/home/insights.html",
      "title": "KPMG Insights",
      "type": "feed",
      "url": "rsshub://kpmg/insights"
    },
    {
      "description": "KPMG Insights - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "220072422980998144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://kpmg.com/cn/zh/home/insights.html",
      "title": "KPMG Insights",
      "type": "feed",
      "url": "rsshub://kpmg/insights/zh"
    }
  ],
  "url": "kpmg.com/xx/en/home/insights.html",
  "zh": {
    "name": "洞察"
  }
}
```
