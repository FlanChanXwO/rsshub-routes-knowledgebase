# Misskey - User timeline

## Coverage
`index-only`

## Route
- Namespace: `misskey`
- Namespace Name: `Misskey`
- Route Path: `/users/notes/:username/:routeParams?`
- Route Name: `User timeline`
- Example: `/misskey/users/notes/support@misskey.io`
- URL: `misskey.io`
- Language: `en`
- Categories: `social-media`
- Maintainers: `siygle, SnowAgar25, HanaokaYuzu`
- Source Location: `user-timeline.ts`
- Source Module: `() => import('@/routes/misskey/user-timeline.ts')`

## Description
_None_

## Parameters
- `username`: Misskey username in the format of username@instance.domain
- `routeParams`: | Key               | Description                             | Accepted Values | Default |
| ----------------- | --------------------------------------- | --------------- | ------- |
| withRenotes       | Include renotes in the timeline         | 0/1/true/false  | false   |
| mediaOnly         | Only return posts containing media      | 0/1/true/false  | false   |
| simplifyAuthor    | Simplify author field in feed items     | 0/1/true/false  | false   |

Note: `withRenotes` and `mediaOnly` are mutually exclusive and cannot both be set to true.

Examples:
- /misskey/users/notes/mttb2ccp@misskey.io/withRenotes=true
- /misskey/users/notes/mttb2ccp@misskey.io/mediaOnly=true


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
    "social-media"
  ],
  "example": "/misskey/users/notes/support@misskey.io",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user-timeline.ts",
  "maintainers": [
    "siygle",
    "SnowAgar25",
    "HanaokaYuzu"
  ],
  "module": "() => import('@/routes/misskey/user-timeline.ts')",
  "name": "User timeline",
  "parameters": {
    "routeParams": "\n| Key               | Description                             | Accepted Values | Default |\n| ----------------- | --------------------------------------- | --------------- | ------- |\n| withRenotes       | Include renotes in the timeline         | 0/1/true/false  | false   |\n| mediaOnly         | Only return posts containing media      | 0/1/true/false  | false   |\n| simplifyAuthor    | Simplify author field in feed items     | 0/1/true/false  | false   |\n\nNote: `withRenotes` and `mediaOnly` are mutually exclusive and cannot both be set to true.\n\nExamples:\n- /misskey/users/notes/mttb2ccp@misskey.io/withRenotes=true\n- /misskey/users/notes/mttb2ccp@misskey.io/mediaOnly=true",
    "username": "Misskey username in the format of username@instance.domain"
  },
  "path": "/users/notes/:username/:routeParams?",
  "view": 1
}
```
