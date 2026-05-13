# KPMG - Insights

## Coverage
`index-only`

## Route
- Namespace: `kpmg`
- Namespace Name: `KPMG`
- Route Path: `/insights/:lang?`
- Route Name: `Insights`
- Example: `/kpmg/insights`
- URL: `kpmg.com/xx/en/home/insights.html`
- Language: `en`
- Categories: `other`
- Maintainers: `LogicJake`
- Source Location: `insights.tsx`
- Source Module: `() => import('@/routes/kpmg/insights.tsx')`

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
  "example": "/kpmg/insights",
  "location": "insights.tsx",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/kpmg/insights.tsx')",
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
  "url": "kpmg.com/xx/en/home/insights.html",
  "zh": {
    "name": "洞察"
  }
}
```
