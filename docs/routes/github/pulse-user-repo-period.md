# GitHub - Repo Pulse

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/pulse/:user/:repo/:period?`
- Route Name: `Repo Pulse`
- Example: `/github/pulse/DIYgod/RSSHub`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `jameschensmith`
- Source Location: `pulse.tsx`
- Source Module: `() => import('@/routes/github/pulse.tsx')`

## Description
_None_

## Parameters
- `user`: User name
- `repo`: Repo name
- `period`: Time frame, selected from a repository's Pulse/Insights page. Possible values are: `daily`, `halfweekly`, `weekly`, or `monthly`. Default: `weekly`. If your RSS client supports it, consider aligning the polling frequency of the feed to the period.


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
  - `github.com/:user/:repo/pulse`
  - `github.com/:user/:repo/pulse/:period`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/pulse/DIYgod/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "pulse.tsx",
  "maintainers": [
    "jameschensmith"
  ],
  "module": "() => import('@/routes/github/pulse.tsx')",
  "name": "Repo Pulse",
  "parameters": {
    "period": "Time frame, selected from a repository's Pulse/Insights page. Possible values are: `daily`, `halfweekly`, `weekly`, or `monthly`. Default: `weekly`. If your RSS client supports it, consider aligning the polling frequency of the feed to the period.",
    "repo": "Repo name",
    "user": "User name"
  },
  "path": "/pulse/:user/:repo/:period?",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/pulse",
        "github.com/:user/:repo/pulse/:period"
      ]
    }
  ]
}
```
