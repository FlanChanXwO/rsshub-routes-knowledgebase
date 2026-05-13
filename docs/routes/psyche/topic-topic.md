# Psyche - Topics

## Coverage
`index-only`

## Route
- Namespace: `psyche`
- Namespace Name: `Psyche`
- Route Path: `/topic/:topic`
- Route Name: `Topics`
- Example: `/psyche/topic/therapeia`
- URL: `psyche.co`
- Language: `en`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/psyche/topic.ts')`

## Description
Supported categories: Therapeia, Eudaimonia, and Poiesis.

## Parameters
- `topic`: Topic


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `psyche.co/:topic`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Supported categories: Therapeia, Eudaimonia, and Poiesis.",
  "example": "/psyche/topic/therapeia",
  "location": "topic.ts",
  "maintainers": [
    "emdoe"
  ],
  "module": "() => import('@/routes/psyche/topic.ts')",
  "name": "Topics",
  "parameters": {
    "topic": "Topic"
  },
  "path": "/topic/:topic",
  "radar": [
    {
      "source": [
        "psyche.co/:topic"
      ]
    }
  ]
}
```
