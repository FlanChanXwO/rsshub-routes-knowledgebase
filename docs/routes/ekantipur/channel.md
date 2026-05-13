# Ekantipur / कान्तिपुर (Nepal) - Full Article RSS

## Coverage
`index-only`

## Route
- Namespace: `ekantipur`
- Namespace Name: `Ekantipur / कान्तिपुर (Nepal)`
- Route Path: `/:channel?`
- Route Name: `Full Article RSS`
- Example: `/ekantipur/news`
- URL: `ekantipur.com`
- Language: `ne`
- Categories: `traditional-media`
- Maintainers: `maniche04`
- Source Location: `issue.ts`
- Source Module: `() => import('@/routes/ekantipur/issue.ts')`

## Description
Channels:

| समाचार | अर्थ / वाणिज्य | विचार     | खेलकुद   | उपत्यका     | मनोरञ्जन         | फोटोफिचर          | फिचर     | विश्व    | ब्लग   |
| ---- | -------- | ------- | ------ | -------- | ------------- | -------------- | ------- | ----- | ---- |
| news | business | opinion | sports | national | entertainment | photo_feature | feature | world | blog |

## Parameters
- `channel`: Find it in the ekantipur.com menu or pick from the list below:


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
  - `ekantipur.com/:channel`
- `target`: `/:channel`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Channels:\n\n| समाचार | अर्थ / वाणिज्य | विचार     | खेलकुद   | उपत्यका     | मनोरञ्जन         | फोटोफिचर          | फिचर     | विश्व    | ब्लग   |\n| ---- | -------- | ------- | ------ | -------- | ------------- | -------------- | ------- | ----- | ---- |\n| news | business | opinion | sports | national | entertainment | photo_feature | feature | world | blog |",
  "example": "/ekantipur/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "issue.ts",
  "maintainers": [
    "maniche04"
  ],
  "module": "() => import('@/routes/ekantipur/issue.ts')",
  "name": "Full Article RSS",
  "parameters": {
    "channel": "Find it in the ekantipur.com menu or pick from the list below:"
  },
  "path": "/:channel?",
  "radar": [
    {
      "source": [
        "ekantipur.com/:channel"
      ],
      "target": "/:channel"
    }
  ]
}
```
