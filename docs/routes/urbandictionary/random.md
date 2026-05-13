# Urban Dictionary - Random words

## Coverage
`index-only`

## Route
- Namespace: `urbandictionary`
- Namespace Name: `Urban Dictionary`
- Route Path: `/random`
- Route Name: `Random words`
- Example: `/urbandictionary/random`
- URL: `urbandictionary.com/random.php`
- Language: `en`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `random.tsx`
- Source Module: `() => import('@/routes/urbandictionary/random.tsx')`

## Description
_None_

## Parameters
_None_


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
  - `urbandictionary.com/random.php`
  - `urbandictionary.com/`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/urbandictionary/random",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "random.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/urbandictionary/random.tsx')",
  "name": "Random words",
  "parameters": {},
  "path": "/random",
  "radar": [
    {
      "source": [
        "urbandictionary.com/random.php",
        "urbandictionary.com/"
      ]
    }
  ],
  "url": "urbandictionary.com/random.php"
}
```
