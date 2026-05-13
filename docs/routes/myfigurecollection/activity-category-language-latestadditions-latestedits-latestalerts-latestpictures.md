# MyFigureCollection - Activity

## Coverage
`index-only`

## Route
- Namespace: `myfigurecollection`
- Namespace Name: `MyFigureCollection`
- Route Path: `/activity/:category?/:language?/:latestAdditions?/:latestEdits?/:latestAlerts?/:latestPictures?`
- Route Name: `Activity`
- Example: `/myfigurecollection/activity`
- URL: `zh.myfigurecollection.net/browse`
- Language: `en`
- Categories: `shopping`
- Maintainers: `nczitzk`
- Source Location: `activity.tsx`
- Source Module: `() => import('@/routes/myfigurecollection/activity.tsx')`

## Description
Category

| Figures | Goods | Media |
| ------- | ----- | ----- |
| 0       | 1     | 2     |

  Language

| Id | Language   |
| -- | ---------- |
|    | en         |
| de | Deutsch    |
| es | Español    |
| fi | Suomeksi   |
| fr | Français   |
| it | Italiano   |
| ja | 日本語     |
| nl | Nederlands |
| no | Norsk      |
| pl | Polski     |
| pt | Português  |
| ru | Русский    |
| sv | Svenska    |
| zh | 中文       |

## Parameters
- `category`: Category, Figures by default
- `language`: Language, as above, `en` by default
- `latestAdditions`: Latest Additions, on as `1` by default, off as `0`
- `latestEdits`: Changes, on as `1` by default, off as `0`
- `latestAlerts`: Alerts, on as `1` by default, off as `0`
- `latestPictures`: Pictures, on as `1` by default, off as `0`


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
  - `zh.myfigurecollection.net/browse`
  - `zh.myfigurecollection.net/`
- `target`: `/:category?/:language?`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "Category\n\n| Figures | Goods | Media |\n| ------- | ----- | ----- |\n| 0       | 1     | 2     |\n\n  Language\n\n| Id | Language   |\n| -- | ---------- |\n|    | en         |\n| de | Deutsch    |\n| es | Español    |\n| fi | Suomeksi   |\n| fr | Français   |\n| it | Italiano   |\n| ja | 日本語     |\n| nl | Nederlands |\n| no | Norsk      |\n| pl | Polski     |\n| pt | Português  |\n| ru | Русский    |\n| sv | Svenska    |\n| zh | 中文       |",
  "example": "/myfigurecollection/activity",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "activity.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/myfigurecollection/activity.tsx')",
  "name": "Activity",
  "parameters": {
    "category": "Category, Figures by default",
    "language": "Language, as above, `en` by default",
    "latestAdditions": "Latest Additions, on as `1` by default, off as `0`",
    "latestAlerts": "Alerts, on as `1` by default, off as `0`",
    "latestEdits": "Changes, on as `1` by default, off as `0`",
    "latestPictures": "Pictures, on as `1` by default, off as `0`"
  },
  "path": "/activity/:category?/:language?/:latestAdditions?/:latestEdits?/:latestAlerts?/:latestPictures?",
  "radar": [
    {
      "source": [
        "zh.myfigurecollection.net/browse",
        "zh.myfigurecollection.net/"
      ],
      "target": "/:category?/:language?"
    }
  ],
  "url": "zh.myfigurecollection.net/browse"
}
```
