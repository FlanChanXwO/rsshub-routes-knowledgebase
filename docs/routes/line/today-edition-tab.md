# LINE - TODAY

## Coverage
`index-only`

## Route
- Namespace: `line`
- Namespace Name: `LINE`
- Route Path: `/today/:edition?/:tab?`
- Route Name: `TODAY`
- Example: `/line/today`
- URL: `today.line.me/`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `today.ts`
- Source Module: `() => import('@/routes/line/today.ts')`

## Description
Edition

| Taiwan | Thailand | Hong Kong |
| ------ | -------- | --------- |
| tw     | th       | hk        |

## Parameters
- `edition`: Edition, see below, Taiwan by default
- `tab`: Tag, can be found in URL, `top` by default


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `today.line.me/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Edition\n\n| Taiwan | Thailand | Hong Kong |\n| ------ | -------- | --------- |\n| tw     | th       | hk        |",
  "example": "/line/today",
  "location": "today.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/line/today.ts')",
  "name": "TODAY",
  "parameters": {
    "edition": "Edition, see below, Taiwan by default",
    "tab": "Tag, can be found in URL, `top` by default"
  },
  "path": "/today/:edition?/:tab?",
  "radar": [
    {
      "source": [
        "today.line.me/"
      ]
    }
  ],
  "url": "today.line.me/"
}
```
