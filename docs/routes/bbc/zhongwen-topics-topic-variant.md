# BBC - Topics - BBC News 中文

## Coverage
`index-only`

## Route
- Namespace: `bbc`
- Namespace Name: `BBC`
- Route Path: `/zhongwen/topics/:topic/:variant?`
- Route Name: `Topics - BBC News 中文`
- Example: `/bbc/zhongwen/topics/ckr7mn6r003t`
- URL: `bbc.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `topic-zhongwen.ts`
- Source Module: `() => import('@/routes/bbc/topic-zhongwen.ts')`

## Description
_None_

## Parameters
- `topic`: The topic ID to fetch news for, can be found in the URL.
- `variant`: {"default": "trad", "description": "The language variant.", "options": [{"label": "简", "value": "simp"}, {"label": "繁", "value": "trad"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bbc.com/zhongwen/topics/:topic/:variant`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/bbc/zhongwen/topics/ckr7mn6r003t",
  "location": "topic-zhongwen.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/bbc/topic-zhongwen.ts')",
  "name": "Topics - BBC News 中文",
  "parameters": {
    "topic": "The topic ID to fetch news for, can be found in the URL.",
    "variant": {
      "default": "trad",
      "description": "The language variant.",
      "options": [
        {
          "label": "简",
          "value": "simp"
        },
        {
          "label": "繁",
          "value": "trad"
        }
      ]
    }
  },
  "path": "/zhongwen/topics/:topic/:variant?",
  "radar": [
    {
      "source": [
        "www.bbc.com/zhongwen/topics/:topic/:variant"
      ]
    }
  ]
}
```
