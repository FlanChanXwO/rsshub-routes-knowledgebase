# web.dev - Series

## Coverage
`index-only`

## Route
- Namespace: `web`
- Namespace Name: `web.dev`
- Route Path: `/web/series/:seriesName`
- Route Name: `Series`
- Example: `/web/series/new-to-the-web`
- URL: `web.dev`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `KarasuShin`
- Source Location: `series.ts`
- Source Module: `_None_`

## Description
::: tip
The `seriesName` can be extracted from the Series page URL: `https://web.dev/series/:seriesName`
:::

## Parameters
- `seriesName`: topic name in the series section


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `web.dev/series/:seriesName`
- `target`: `/series/:seriesName`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "::: tip\nThe `seriesName` can be extracted from the Series page URL: `https://web.dev/series/:seriesName`\n:::",
  "example": "/web/series/new-to-the-web",
  "heat": 0,
  "location": "series.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "Series",
  "parameters": {
    "seriesName": "topic name in the series section"
  },
  "path": "/series/:seriesName",
  "radar": [
    {
      "source": [
        "web.dev/series/:seriesName"
      ],
      "target": "/series/:seriesName"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
