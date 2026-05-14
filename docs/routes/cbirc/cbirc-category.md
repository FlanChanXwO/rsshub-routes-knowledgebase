# 中国银行保险监督管理委员会 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `cbirc`
- Namespace Name: `中国银行保险监督管理委员会`
- Route Path: `/cbirc/:category?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `cbirc.gov.cn`
- Language: `_None_`
- Categories: `other`
- Maintainers: `JkCheung`
- Source Location: `index.ts`
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
  - `cbirc.gov.cn/:category`
  - `cbirc.gov.cn/`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "heat": 4,
  "location": "index.ts",
  "maintainers": [
    "JkCheung"
  ],
  "name": "Unknown",
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "cbirc.gov.cn/:category",
        "cbirc.gov.cn/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-10-07T13:08:08.543Z",
      "errorMessage": "[GET] \"http://www.cbirc.gov.cn/cn/static/data/DocInfo/SelectDocByItemIdAndChild/data_itemId=925,pageIndex=1,pageSize=18.json\": <no response> fetch failed\n",
      "id": "198372079645781014",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://cbirc/ggtz"
    },
    {
      "description": null,
      "errorAt": "2025-10-07T13:08:19.233Z",
      "errorMessage": "Failed to fetch\n",
      "id": "198372079645781012",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://cbirc/tjxx"
    }
  ]
}
```
