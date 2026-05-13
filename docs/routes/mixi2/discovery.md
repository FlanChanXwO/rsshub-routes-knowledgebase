# mixi2 - 発見

## Coverage
`index-only`

## Route
- Namespace: `mixi2`
- Namespace Name: `mixi2`
- Route Path: `/discovery`
- Route Name: `発見`
- Example: `/mixi2/discovery`
- URL: `mixi.social`
- Language: `ja`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `discovery.ts`
- Source Module: `() => import('@/routes/mixi2/discovery.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `supportRadar`: true
- `requireConfig`: [{"description": "mixi2ログイン後の情報。ブラウザのコンソールでクッキーから `auth_token` の値を取得してください", "name": "MIXI2_AUTH_TOKEN"}, {"description": "mixi2ログイン後の情報。ブラウザのコンソールでリクエストヘッダーから `x-auth-key` の値を取得してください", "name": "MIXI2_AUTH_KEY"}]

## Radar
### Rule 1
- `source`:
  - `mixi.social/home/discovery`
- `target`: `/discovery`
- `title`: `発見`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/mixi2/discovery",
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
  "location": "discovery.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/mixi2/discovery.ts')",
  "name": "発見",
  "path": "/discovery",
  "radar": [
    {
      "source": [
        "mixi.social/home/discovery"
      ],
      "target": "/discovery",
      "title": "発見"
    }
  ],
  "view": 1
}
```
