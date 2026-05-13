# ファミ通 - Category

## Coverage
`index-only`

## Route
- Namespace: `famitsu`
- Namespace Name: `ファミ通`
- Route Path: `/category/:category?`
- Route Name: `Category`
- Example: `/famitsu/category/new-article`
- URL: `famitsu.com`
- Language: `ja`
- Categories: `game`
- Maintainers: `TonyRL`
- Source Location: `category.tsx`
- Source Module: `() => import('@/routes/famitsu/category.tsx')`

## Description
| 新着        | Switch | PS5 | PS4 | PC ゲーム | ニュース | 動画   | 特集・企画記事  | インタビュー | 取材・リポート | レビュー | インディーゲーム |
| ----------- | ------ | --- | --- | --------- | -------- | ------ | --------------- | ------------ | -------------- | -------- | ---------------- |
| new-article | switch | ps5 | ps4 | pc-game   | news     | videos | special-article | interview    | event-report   | review   | indie-game       |

## Parameters
- `category`: Category, see table below, `new-article` by default


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.famitsu.com/category/:category/page/1`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 新着        | Switch | PS5 | PS4 | PC ゲーム | ニュース | 動画   | 特集・企画記事  | インタビュー | 取材・リポート | レビュー | インディーゲーム |\n| ----------- | ------ | --- | --- | --------- | -------- | ------ | --------------- | ------------ | -------------- | -------- | ---------------- |\n| new-article | switch | ps5 | ps4 | pc-game   | news     | videos | special-article | interview    | event-report   | review   | indie-game       |",
  "example": "/famitsu/category/new-article",
  "location": "category.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/famitsu/category.tsx')",
  "name": "Category",
  "parameters": {
    "category": "Category, see table below, `new-article` by default"
  },
  "path": "/category/:category?",
  "radar": [
    {
      "source": [
        "www.famitsu.com/category/:category/page/1"
      ]
    }
  ]
}
```
