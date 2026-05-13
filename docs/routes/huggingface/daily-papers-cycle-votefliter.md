# Huggingface - Daily Papers

## Coverage
`index-only`

## Route
- Namespace: `huggingface`
- Namespace Name: `Huggingface`
- Route Path: `/daily-papers/:cycle?/:voteFliter?`
- Route Name: `Daily Papers`
- Example: `/huggingface/daily-papers/week/50`
- URL: `huggingface.co/papers`
- Language: `en`
- Categories: `programming`
- Maintainers: `zeyugao, ovo-tim`
- Source Location: `daily-papers.ts`
- Source Module: `() => import('@/routes/huggingface/daily-papers.ts')`

## Description
_None_

## Parameters
- `cycle`: The publication cycle you want to follow. Choose from: date, week, month. Default: date
- `voteFliter`: Filter papers by vote count.


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
  - `huggingface.co/papers/:cycle`
- `target`: `/daily-papers/:cycle`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/huggingface/daily-papers/week/50",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "daily-papers.ts",
  "maintainers": [
    "zeyugao",
    "ovo-tim"
  ],
  "module": "() => import('@/routes/huggingface/daily-papers.ts')",
  "name": "Daily Papers",
  "parameters": {
    "cycle": "The publication cycle you want to follow. Choose from: date, week, month. Default: date",
    "voteFliter": "Filter papers by vote count."
  },
  "path": "/daily-papers/:cycle?/:voteFliter?",
  "radar": [
    {
      "source": [
        "huggingface.co/papers/:cycle"
      ],
      "target": "/daily-papers/:cycle"
    }
  ],
  "url": "huggingface.co/papers"
}
```
