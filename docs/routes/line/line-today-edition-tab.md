# LINE - TODAY

## Coverage
`index-only`

## Route
- Namespace: `line`
- Namespace Name: `LINE`
- Route Path: `/line/today/:edition?/:tab?`
- Route Name: `TODAY`
- Example: `/line/today`
- URL: `today.line.me/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `today.ts`
- Source Module: `_None_`

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
  "heat": 89,
  "location": "today.ts",
  "maintainers": [
    "nczitzk"
  ],
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
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "焦點 - Line Today - Powered by RSSHub",
      "errorAt": "2026-07-15T04:43:46.071Z",
      "errorMessage": "403 \nFailed to fetch\n",
      "id": "59767191179278336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://today.line.me/tw/v2/tab/top",
      "title": "焦點 - Line Today",
      "type": "feed",
      "url": "rsshub://line/today"
    },
    {
      "description": "焦點 - Line Today - Powered by RSSHub",
      "errorAt": "2026-07-15T04:44:15.145Z",
      "errorMessage": "Failed to fetch\nFailed to fetch\n",
      "id": "79089289951263744",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://today.line.me/tw/v2/tab/top",
      "title": "焦點 - Line Today",
      "type": "feed",
      "url": "rsshub://line/today/tw"
    }
  ],
  "url": "today.line.me/"
}
```
