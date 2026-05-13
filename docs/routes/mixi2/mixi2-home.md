# mixi2 - フォロー中

## Coverage
`index-only`

## Route
- Namespace: `mixi2`
- Namespace Name: `mixi2`
- Route Path: `/mixi2/home`
- Route Name: `フォロー中`
- Example: `/mixi2/home`
- URL: `mixi.social`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `home.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "mixi2ログイン後の情報。ブラウザのコンソールでクッキーから `auth_token` の値を取得してください", "name": "MIXI2_AUTH_TOKEN"}, {"description": "mixi2ログイン後の情報。ブラウザのコンソールでリクエストヘッダーから `x-auth-key` の値を取得してください", "name": "MIXI2_AUTH_KEY"}]
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `mixi.social/home`
- `target`: `/home`
- `title`: `フォロー中`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/mixi2/home",
  "features": {
    "requireConfig": [
      {
        "description": "mixi2ログイン後の情報。ブラウザのコンソールでクッキーから `auth_token` の値を取得してください",
        "name": "MIXI2_AUTH_TOKEN"
      },
      {
        "description": "mixi2ログイン後の情報。ブラウザのコンソールでリクエストヘッダーから `x-auth-key` の値を取得してください",
        "name": "MIXI2_AUTH_KEY"
      }
    ],
    "supportRadar": true
  },
  "heat": 0,
  "location": "home.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "フォロー中",
  "path": "/home",
  "radar": [
    {
      "source": [
        "mixi.social/home"
      ],
      "target": "/home",
      "title": "フォロー中"
    }
  ],
  "topFeeds": [],
  "view": 1
}
```
