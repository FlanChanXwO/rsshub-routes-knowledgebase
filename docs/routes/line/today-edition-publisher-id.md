# LINE - TODAY - Channel

## Coverage
`index-only`

## Route
- Namespace: `line`
- Namespace Name: `LINE`
- Route Path: `/today/:edition/publisher/:id`
- Route Name: `TODAY - Channel`
- Example: `/line/today/th/publisher/101048`
- URL: `today.line.me`
- Language: `en`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `publisher.ts`
- Source Module: `() => import('@/routes/line/publisher.ts')`

## Description
_None_

## Parameters
- `edition`: Edition, see table above
- `id`: Channel ID, can be found in URL


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `today.line.me/:edition/v2/publisher/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/line/today/th/publisher/101048",
  "location": "publisher.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/line/publisher.ts')",
  "name": "TODAY - Channel",
  "parameters": {
    "edition": "Edition, see table above",
    "id": "Channel ID, can be found in URL"
  },
  "path": "/today/:edition/publisher/:id",
  "radar": [
    {
      "source": [
        "today.line.me/:edition/v2/publisher/:id"
      ]
    }
  ]
}
```
