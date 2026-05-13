# Greasy Fork - Script Update

## Coverage
`index-only`

## Route
- Namespace: `greasyfork`
- Namespace Name: `Greasy Fork`
- Route Path: `/:language/:domain?`
- Route Name: `Script Update`
- Example: `/greasyfork/en/google.com`
- URL: `greasyfork.org`
- Language: `en`
- Categories: `program-update`
- Maintainers: `imlonghao, miles170`
- Source Location: `scripts.ts`
- Source Module: `() => import('@/routes/greasyfork/scripts.ts')`

## Description
| Sort            | Description    |
| --------------- | -------------- |
| today           | Daily installs |
| total_installs | Total installs |
| ratings         | Ratings        |
| created         | Created date   |
| updated         | Updated date   |
| name            | Name           |

## Parameters
- `language`: language, located on the top right corner of Greasy Fork's search page, set to `all` for including all languages
- `domain`: the script's target domain


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
  - `greasyfork.org/:language`
  - `greasyfork.org/:language/scripts/by-site/:domain?`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "| Sort            | Description    |\n| --------------- | -------------- |\n| today           | Daily installs |\n| total_installs | Total installs |\n| ratings         | Ratings        |\n| created         | Created date   |\n| updated         | Updated date   |\n| name            | Name           |",
  "example": "/greasyfork/en/google.com",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "scripts.ts",
  "maintainers": [
    "imlonghao",
    "miles170"
  ],
  "module": "() => import('@/routes/greasyfork/scripts.ts')",
  "name": "Script Update",
  "parameters": {
    "domain": "the script's target domain",
    "language": "language, located on the top right corner of Greasy Fork's search page, set to `all` for including all languages"
  },
  "path": [
    "/:language/:domain?",
    "/scripts/sort/:sort/:language?"
  ],
  "radar": [
    {
      "source": [
        "greasyfork.org/:language",
        "greasyfork.org/:language/scripts/by-site/:domain?"
      ]
    }
  ]
}
```
