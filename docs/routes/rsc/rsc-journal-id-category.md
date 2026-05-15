# Royal Society of Chemistry - Journal

## Coverage
`index-only`

## Route
- Namespace: `rsc`
- Namespace Name: `Royal Society of Chemistry`
- Route Path: `/rsc/journal/:id/:category?`
- Route Name: `Journal`
- Example: `/rsc/journal/ta`
- URL: `pubs.rsc.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `journal.tsx`
- Source Module: `_None_`

## Description
::: tip
All journals at [Current journals](https://pubs.rsc.org/en/journals)
:::

| All Recent Articles | Advance Articles |
| ------------------- | ---------------- |
| allrecentarticles   | advancearticles  |

## Parameters
- `id`: Journal id, can be found in URL
- `category`: Category, see below, All Recent Articles by default


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
    "journal"
  ],
  "description": "::: tip\nAll journals at [Current journals](https://pubs.rsc.org/en/journals)\n:::\n\n| All Recent Articles | Advance Articles |\n| ------------------- | ---------------- |\n| allrecentarticles   | advancearticles  |",
  "example": "/rsc/journal/ta",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 11,
  "location": "journal.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Journal",
  "parameters": {
    "category": "Category, see below, All Recent Articles by default",
    "id": "Journal id, can be found in URL"
  },
  "path": "/journal/:id/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:37:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Journal of Materials Chemistry A - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "175094017782230016",
      "image": "https://pubs.rsc.org/en/Image/Get?imageInfo.ImageType=CoverIssue&imageInfo.ImageIdentifier.SerCode=ta&imageInfo.ImageIdentifier.IssueId=TA014028&imageInfo.ImageIdentifier.Year=2026",
      "ownerUserId": null,
      "siteUrl": "https://pubs.rsc.org/en/journals/journalissues/ta#!recentarticles",
      "title": "Journal of Materials Chemistry A",
      "type": "feed",
      "url": "rsshub://rsc/journal/ta"
    },
    {
      "description": "Energy & Environmental Science - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "159483253180956672",
      "image": "https://pubs.rsc.org/en/Image/Get?imageInfo.ImageType=CoverIssue&imageInfo.ImageIdentifier.SerCode=ee&imageInfo.ImageIdentifier.IssueId=EE019007&imageInfo.ImageIdentifier.Year=2026",
      "ownerUserId": null,
      "siteUrl": "https://pubs.rsc.org/en/journals/journalissues/ee#!recentarticles",
      "title": "Energy & Environmental Science",
      "type": "feed",
      "url": "rsshub://rsc/journal/ee"
    }
  ]
}
```
