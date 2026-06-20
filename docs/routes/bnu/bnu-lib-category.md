# 北京师范大学 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `bnu`
- Namespace Name: `北京师范大学`
- Route Path: `/bnu/lib/:category?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `bs.bnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `TonyRL`
- Source Location: `lib.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.lib.bnu.edu.cn/:category/index.htm`
- `target`: `/lib/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "heat": 2,
  "location": "lib.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Unknown",
  "path": "/lib/:category?",
  "radar": [
    {
      "source": [
        "www.lib.bnu.edu.cn/:category/index.htm"
      ],
      "target": "/lib/:category"
    }
  ],
  "topFeeds": [
    {
      "description": "北京师范大学图书馆 | 北京师范大学图书馆 - Powered by RSSHub",
      "errorAt": "2025-12-22T09:40:10.256Z",
      "errorMessage": "[GET] \"http://www.lib.bnu.edu.cn/zydt/index.htm\": 404 Not Found\n",
      "id": "63261228702728212",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.lib.bnu.edu.cn/zydt/index.htm",
      "title": "北京师范大学图书馆 | 北京师范大学图书馆",
      "type": "feed",
      "url": "rsshub://bnu/lib/zydt"
    }
  ]
}
```
