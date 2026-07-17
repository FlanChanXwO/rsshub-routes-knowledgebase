# Misskey - User timeline

## Coverage
`index-only`

## Route
- Namespace: `misskey`
- Namespace Name: `Misskey`
- Route Path: `/misskey/users/notes/:username/:routeParams?`
- Route Name: `User timeline`
- Example: `/misskey/users/notes/support@misskey.io`
- URL: `misskey.io`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `siygle, SnowAgar25, HanaokaYuzu`
- Source Location: `user-timeline.ts`
- Source Module: `_None_`

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
  "heat": 32,
  "location": "user-timeline.ts",
  "maintainers": [
    "siygle",
    "SnowAgar25",
    "HanaokaYuzu"
  ],
  "name": "User timeline",
  "parameters": {
    "routeParams": "\n| Key               | Description                             | Accepted Values | Default |\n| ----------------- | --------------------------------------- | --------------- | ------- |\n| withRenotes       | Include renotes in the timeline         | 0/1/true/false  | false   |\n| mediaOnly         | Only return posts containing media      | 0/1/true/false  | false   |\n| simplifyAuthor    | Simplify author field in feed items     | 0/1/true/false  | false   |\n\nNote: `withRenotes` and `mediaOnly` are mutually exclusive and cannot both be set to true.\n\nExamples:\n- /misskey/users/notes/mttb2ccp@misskey.io/withRenotes=true\n- /misskey/users/notes/mttb2ccp@misskey.io/mediaOnly=true",
    "username": "Misskey username in the format of username@instance.domain"
  },
  "path": "/users/notes/:username/:routeParams?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "User timeline for umebachi@misskey.io on misskey.io - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "114350575541664768",
      "image": "https://proxy.misskeyusercontent.jp/avatar/media.misskeyusercontent.jp%2Fio%2Fwebpublic-b3ca10e5-264d-47ab-acc7-f44ae8be0f6a.webp%3Fsensitive%3Dtrue?avatar=1",
      "ownerUserId": null,
      "siteUrl": "https://misskey.io/@umebachi",
      "title": "User timeline for umebachi@misskey.io on misskey.io",
      "type": "feed",
      "url": "rsshub://misskey/users/notes/umebachi@misskey.io/mediaOnly=true"
    },
    {
      "description": "User timeline for ixy@misskey.io on misskey.io - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64831126205828096",
      "image": "https://proxy.misskeyusercontent.jp/avatar.webp?url=https%3A%2F%2Fmedia.misskeyusercontent.jp%2Fio%2F4d3bc962-189d-4ea5-8417-f622daa6d5d1.png&avatar=1",
      "ownerUserId": null,
      "siteUrl": "https://misskey.io/@ixy",
      "title": "User timeline for ixy@misskey.io on misskey.io",
      "type": "feed",
      "url": "rsshub://misskey/users/notes/ixy@misskey.io"
    }
  ],
  "view": 1
}
```
