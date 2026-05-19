# Deepin - BBS Home Page

## Coverage
`index-only`

## Route
- Namespace: `deepin`
- Namespace Name: `Deepin`
- Route Path: `/deepin/homepage/:user_id`
- Route Name: `BBS Home Page`
- Example: `/deepin/homepage/78326`
- URL: `bbs.deepin.org`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `tensor-tech`
- Source Location: `homepage.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user_id`: user id


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `bbs.deepin.org/user/:user_id`
- `target`: `/homepage/:user_id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/deepin/homepage/78326",
  "heat": 2,
  "location": "homepage.ts",
  "maintainers": [
    "tensor-tech"
  ],
  "name": "BBS Home Page",
  "parameters": {
    "user_id": "user id"
  },
  "path": "/homepage/:user_id",
  "radar": [
    {
      "source": [
        "bbs.deepin.org/user/:user_id"
      ],
      "target": "/homepage/:user_id"
    }
  ],
  "topFeeds": [
    {
      "description": "广雅居士/deepin论坛主页 - Powered by RSSHub",
      "errorAt": "2025-08-01T09:57:01.786Z",
      "errorMessage": "[GET] \"https://bbs.deepin.org/api/v1/user/thread?date_type=0&limit=10&offset=0&user_id=78326\": 403 Forbidden\n",
      "id": "63580812692062208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.deepin.org/user/78326",
      "title": "广雅居士/deepin论坛主页",
      "type": "feed",
      "url": "rsshub://deepin/homepage/78326"
    }
  ]
}
```
