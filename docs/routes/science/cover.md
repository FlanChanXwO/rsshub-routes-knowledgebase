# Science Magazine - Cover Story

## Coverage
`index-only`

## Route
- Namespace: `science`
- Namespace Name: `Science Magazine`
- Route Path: `/cover`
- Route Name: `Cover Story`
- Example: `/science/cover`
- URL: `science.org/`
- Language: `en`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `cover.tsx`
- Source Module: `() => import('@/routes/science/cover.tsx')`

## Description
Subscribe to the cover images of Science journals, and get the latest publication updates in time.

  Including 'Science', 'Science Advances', 'Science Immunology', 'Science Robotics', 'Science Signaling' and 'Science Translational Medicine'.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `science.org/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "Subscribe to the cover images of Science journals, and get the latest publication updates in time.\n\n  Including 'Science', 'Science Advances', 'Science Immunology', 'Science Robotics', 'Science Signaling' and 'Science Translational Medicine'.",
  "example": "/science/cover",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cover.tsx",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "module": "() => import('@/routes/science/cover.tsx')",
  "name": "Cover Story",
  "parameters": {},
  "path": "/cover",
  "radar": [
    {
      "source": [
        "science.org/"
      ]
    }
  ],
  "url": "science.org/"
}
```
