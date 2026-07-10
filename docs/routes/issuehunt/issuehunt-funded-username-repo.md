# Issue Hunt - Project Funded

## Coverage
`index-only`

## Route
- Namespace: `issuehunt`
- Namespace Name: `Issue Hunt`
- Route Path: `/issuehunt/funded/:username/:repo`
- Route Name: `Project Funded`
- Example: `/issuehunt/funded/DIYgod/RSSHub`
- URL: `issuehunt.io`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `running-grass`
- Source Location: `funded.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: Github user/org
- `repo`: Repository name


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/issuehunt/funded/DIYgod/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "funded.ts",
  "maintainers": [
    "running-grass"
  ],
  "name": "Project Funded",
  "parameters": {
    "repo": "Repository name",
    "username": "Github user/org"
  },
  "path": "/funded/:username/:repo",
  "topFeeds": []
}
```
