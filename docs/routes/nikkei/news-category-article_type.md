# The Nikkei 日本経済新聞 - News

## Coverage
`index-only`

## Route
- Namespace: `nikkei`
- Namespace Name: `The Nikkei 日本経済新聞`
- Route Path: `/news/:category/:article_type?`
- Route Name: `News`
- Example: `/nikkei/news/news`
- URL: `nikkei.com`
- Language: `ja`
- Categories: `traditional-media`
- Maintainers: `Arracc, ladeng07`
- Source Location: `news.tsx`
- Source Module: `() => import('@/routes/nikkei/news.tsx')`

## Description
| 総合 | オピニオン | 経済    | 政治     | 金融      | マーケット | ビジネス | マネーのまなび | テック     | 国際          | スポーツ | 社会・調査 | 地域  | 文化    | ライフスタイル |
| ---- | ---------- | ------- | -------- | --------- | ---------- | -------- | -------------- | ---------- | ------------- | -------- | ---------- | ----- | ------- | -------------- |
| news | opinion    | economy | politics | financial | business   | 不支持   | 不支持         | technology | international | sports   | society    | local | culture | lifestyle      |

## Parameters
- `category`: Category, see table below
- `article_type`: Only includes free articles, set `free` to enable, disabled by default


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.nikkei.com/:category/archive`
  - `www.nikkei.com/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 総合 | オピニオン | 経済    | 政治     | 金融      | マーケット | ビジネス | マネーのまなび | テック     | 国際          | スポーツ | 社会・調査 | 地域  | 文化    | ライフスタイル |\n| ---- | ---------- | ------- | -------- | --------- | ---------- | -------- | -------------- | ---------- | ------------- | -------- | ---------- | ----- | ------- | -------------- |\n| news | opinion    | economy | politics | financial | business   | 不支持   | 不支持         | technology | international | sports   | society    | local | culture | lifestyle      |",
  "example": "/nikkei/news/news",
  "location": "news.tsx",
  "maintainers": [
    "Arracc",
    "ladeng07"
  ],
  "module": "() => import('@/routes/nikkei/news.tsx')",
  "name": "News",
  "parameters": {
    "article_type": "Only includes free articles, set `free` to enable, disabled by default",
    "category": "Category, see table below"
  },
  "path": "/news/:category/:article_type?",
  "radar": [
    {
      "source": [
        "www.nikkei.com/:category/archive",
        "www.nikkei.com/:category"
      ],
      "target": "/:category"
    }
  ]
}
```
