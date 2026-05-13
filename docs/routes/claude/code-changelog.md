# Claude - Code Changelog

## Coverage
`index-only`

## Route
- Namespace: `claude`
- Namespace Name: `Claude`
- Route Path: `/code/changelog`
- Route Name: `Code Changelog`
- Example: `/claude/code/changelog`
- URL: `code.claude.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `rmaced0`
- Source Location: `code-changelog.ts`
- Source Module: `() => import('@/routes/claude/code-changelog.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `code.claude.com/docs/en/changelog`
- `target`: `/code/changelog`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/claude/code/changelog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "code-changelog.ts",
  "maintainers": [
    "rmaced0"
  ],
  "module": "() => import('@/routes/claude/code-changelog.ts')",
  "name": "Code Changelog",
  "path": "/code/changelog",
  "radar": [
    {
      "source": [
        "code.claude.com/docs/en/changelog"
      ],
      "target": "/code/changelog"
    }
  ],
  "url": "code.claude.com"
}
```
