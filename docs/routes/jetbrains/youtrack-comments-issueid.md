# JetBrains - YouTrack Issue Comments

## Coverage
`index-only`

## Route
- Namespace: `jetbrains`
- Namespace Name: `JetBrains`
- Route Path: `/youtrack/comments/:issueId`
- Route Name: `YouTrack Issue Comments`
- Example: `/jetbrains/youtrack/comments/IJPL-174543`
- URL: `jetbrains.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `NekoAria`
- Source Location: `comments.ts`
- Source Module: `() => import('@/routes/jetbrains/comments.ts')`

## Description
_None_

## Parameters
- `issueId`: Issue ID (e.g., IJPL-174543)


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `youtrack.jetbrains.com/issue/:issueId`
- `target`: `/youtrack/comments/:issueId`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/jetbrains/youtrack/comments/IJPL-174543",
  "location": "comments.ts",
  "maintainers": [
    "NekoAria"
  ],
  "module": "() => import('@/routes/jetbrains/comments.ts')",
  "name": "YouTrack Issue Comments",
  "parameters": {
    "issueId": "Issue ID (e.g., IJPL-174543)"
  },
  "path": "/youtrack/comments/:issueId",
  "radar": [
    {
      "source": [
        "youtrack.jetbrains.com/issue/:issueId"
      ],
      "target": "/youtrack/comments/:issueId"
    }
  ]
}
```
