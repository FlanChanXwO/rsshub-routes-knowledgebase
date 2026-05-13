# mixi2 - コミュニティ

## Coverage
`index-only`

## Route
- Namespace: `mixi2`
- Namespace Name: `mixi2`
- Route Path: `/community/:id/:media?`
- Route Name: `コミュニティ`
- Example: `/mixi2/community/62e7e813-d242-4c54-a0ee-0aab5b2bbad2`
- URL: `mixi.social`
- Language: `ja`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `community.ts`
- Source Module: `() => import('@/routes/mixi2/community.ts')`

## Description
_None_

## Parameters
- `id`: {"description": "コミュニティID"}
- `media`: {"description": "`media`を入力するとメディアを含むポストのみを取得、デフォルトは空で全てのポストを取得"}


## Features
- `supportRadar`: true
- `requireConfig`: [{"description": "mixi2ログイン後の情報。ブラウザのコンソールでクッキーから `auth_token` の値を取得してください", "name": "MIXI2_AUTH_TOKEN"}, {"description": "mixi2ログイン後の情報。ブラウザのコンソールでリクエストヘッダーから `x-auth-key` の値を取得してください", "name": "MIXI2_AUTH_KEY"}]

## Radar
### Rule 1
- `source`:
  - `mixi.social/communities/:id`
  - `mixi.social/communities/:id/about`
- `target`: `/community/:id`
- `title`: `コミュニティ - ポスト`
### Rule 2
- `source`:
  - `mixi.social/communities/:id`
  - `mixi.social/communities/:id/about`
- `target`: `/community/:id/media`
- `title`: `コミュニティ - メディア`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/mixi2/community/62e7e813-d242-4c54-a0ee-0aab5b2bbad2",
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
  "location": "community.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/mixi2/community.ts')",
  "name": "コミュニティ",
  "parameters": {
    "id": {
      "description": "コミュニティID"
    },
    "media": {
      "description": "`media`を入力するとメディアを含むポストのみを取得、デフォルトは空で全てのポストを取得"
    }
  },
  "path": "/community/:id/:media?",
  "radar": [
    {
      "source": [
        "mixi.social/communities/:id",
        "mixi.social/communities/:id/about"
      ],
      "target": "/community/:id",
      "title": "コミュニティ - ポスト"
    },
    {
      "source": [
        "mixi.social/communities/:id",
        "mixi.social/communities/:id/about"
      ],
      "target": "/community/:id/media",
      "title": "コミュニティ - メディア"
    }
  ],
  "view": 1
}
```
