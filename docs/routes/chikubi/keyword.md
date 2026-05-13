# 乳首ふぇち - Navigation

## Coverage
`index-only`

## Route
- Namespace: `chikubi`
- Namespace Name: `乳首ふぇち`
- Route Path: `/:keyword`
- Route Name: `Navigation`
- Example: `/chikubi`
- URL: `chikubi.jp`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `SnowAgar25`
- Source Location: `navigation.ts`
- Source Module: `() => import('@/routes/chikubi/navigation.ts')`

## Description
| 殿堂 | 動畫 | VR | 漫畫 | 音聲 | CG・イラスト |
| ---- | ----- | -- | ----- | ----- | -- |
| best | video | vr | comic | voice | cg |

## Parameters
- `keyword`: 導覽列，見下表，默認爲最新


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| 殿堂 | 動畫 | VR | 漫畫 | 音聲 | CG・イラスト |\n| ---- | ----- | -- | ----- | ----- | -- |\n| best | video | vr | comic | voice | cg |",
  "example": "/chikubi",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "navigation.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/chikubi/navigation.ts')",
  "name": "Navigation",
  "parameters": {
    "keyword": "導覽列，見下表，默認爲最新"
  },
  "path": "/:keyword"
}
```
