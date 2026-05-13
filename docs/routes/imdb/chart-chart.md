# IMDb - Charts

## Coverage
`index-only`

## Route
- Namespace: `imdb`
- Namespace Name: `IMDb`
- Route Path: `/chart/:chart?`
- Route Name: `Charts`
- Example: `/imdb/chart`
- URL: `www.imdb.com/chart/top/`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `chart.tsx`
- Source Module: `() => import('@/routes/imdb/chart.tsx')`

## Description
| Top 250 Movies | Most Popular Movies | Top 250 TV Shows | Most Popular TV Shows |
| -------------- | ------------------- | ---------------- | --------------------- |
| top            | moviemeter          | toptv            | tvmeter               |

## Parameters
- `chart`: {"default": "top", "description": "The chart to display, `top` by default", "options": [{"label": "Top 250 Movies", "value": "top"}, {"label": "Most Popular Movies", "value": "moviemeter"}, {"label": "Top 250 TV Shows", "value": "toptv"}, {"label": "Most Popular TV Shows", "value": "tvmeter"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.imdb.com/chart/:chart/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| Top 250 Movies | Most Popular Movies | Top 250 TV Shows | Most Popular TV Shows |\n| -------------- | ------------------- | ---------------- | --------------------- |\n| top            | moviemeter          | toptv            | tvmeter               |",
  "example": "/imdb/chart",
  "location": "chart.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/imdb/chart.tsx')",
  "name": "Charts",
  "parameters": {
    "chart": {
      "default": "top",
      "description": "The chart to display, `top` by default",
      "options": [
        {
          "label": "Top 250 Movies",
          "value": "top"
        },
        {
          "label": "Most Popular Movies",
          "value": "moviemeter"
        },
        {
          "label": "Top 250 TV Shows",
          "value": "toptv"
        },
        {
          "label": "Most Popular TV Shows",
          "value": "tvmeter"
        }
      ]
    }
  },
  "path": "/chart/:chart?",
  "radar": [
    {
      "source": [
        "www.imdb.com/chart/:chart/"
      ]
    }
  ],
  "url": "www.imdb.com/chart/top/",
  "view": 5
}
```
