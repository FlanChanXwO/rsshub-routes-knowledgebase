# Sankei Shimbun 産経新聞 - Topic

## Coverage
`index-only`

## Route
- Namespace: `sankei`
- Namespace Name: `Sankei Shimbun 産経新聞`
- Route Path: `/topics/:topic`
- Route Name: `Topic`
- Example: `/sankei/topics/etc_100`
- URL: `sankei.com`
- Language: `ja`
- Categories: `traditional-media`
- Maintainers: `yuikisaito`
- Source Location: `topics.ts`
- Source Module: `() => import('@/routes/sankei/topics.ts')`

## Description
_None_

## Parameters
- `topic`: Topic name (format included in URL). For example, for "Expo 2025 Osaka, Kansai, Japan Special Feature" https://www.sankei.com/tag/topic/etc_100, the value would be etc_100.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sankei.com/tag/topic/:topic`
- `target`: `/topics/:topic`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/sankei/topics/etc_100",
  "location": "topics.ts",
  "maintainers": [
    "yuikisaito"
  ],
  "module": "() => import('@/routes/sankei/topics.ts')",
  "name": "Topic",
  "parameters": {
    "topic": "Topic name (format included in URL). For example, for \"Expo 2025 Osaka, Kansai, Japan Special Feature\" https://www.sankei.com/tag/topic/etc_100, the value would be etc_100."
  },
  "path": [
    "/topics/:topic"
  ],
  "radar": [
    {
      "source": [
        "www.sankei.com/tag/topic/:topic"
      ],
      "target": "/topics/:topic"
    }
  ]
}
```
