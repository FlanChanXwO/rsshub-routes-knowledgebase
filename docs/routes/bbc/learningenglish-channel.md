# BBC - Learning English

## Coverage
`index-only`

## Route
- Namespace: `bbc`
- Namespace Name: `BBC`
- Route Path: `/learningenglish/:channel?`
- Route Name: `Learning English`
- Example: `/bbc/learningenglish/take-away-english`
- URL: `bbc.com`
- Language: `en`
- Categories: `study`
- Maintainers: `Blank0120`
- Source Location: `learningenglish.ts`
- Source Module: `() => import('@/routes/bbc/learningenglish.ts')`

## Description
_None_

## Parameters
- `channel`: {"default": "take-away-english", "description": "英语学习分类栏目", "options": [{"label": "随身英语", "value": "take-away-english"}, {"label": "地道英语", "value": "authentic-real-english"}, {"label": "媒体英语", "value": "media-english"}, {"label": "英语大破解", "value": "lingohack"}, {"label": "一分钟英语", "value": "english-in-a-minute"}, {"label": "短语动词", "value": "phrasal-verbs"}, {"label": "今日短语", "value": "todays-phrase"}, {"label": "你问我答", "value": "q-and-a"}, {"label": "白领英语", "value": "english-at-work"}, {"label": "亲子英语故事", "value": "storytellers"}]}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/bbc/learningenglish/take-away-english",
  "location": "learningenglish.ts",
  "maintainers": [
    "Blank0120"
  ],
  "module": "() => import('@/routes/bbc/learningenglish.ts')",
  "name": "Learning English",
  "parameters": {
    "channel": {
      "default": "take-away-english",
      "description": "英语学习分类栏目",
      "options": [
        {
          "label": "随身英语",
          "value": "take-away-english"
        },
        {
          "label": "地道英语",
          "value": "authentic-real-english"
        },
        {
          "label": "媒体英语",
          "value": "media-english"
        },
        {
          "label": "英语大破解",
          "value": "lingohack"
        },
        {
          "label": "一分钟英语",
          "value": "english-in-a-minute"
        },
        {
          "label": "短语动词",
          "value": "phrasal-verbs"
        },
        {
          "label": "今日短语",
          "value": "todays-phrase"
        },
        {
          "label": "你问我答",
          "value": "q-and-a"
        },
        {
          "label": "白领英语",
          "value": "english-at-work"
        },
        {
          "label": "亲子英语故事",
          "value": "storytellers"
        }
      ]
    }
  },
  "path": "/learningenglish/:channel?"
}
```
