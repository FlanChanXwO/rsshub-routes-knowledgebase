# Engineering.fyi - Tag

## Coverage
`index-only`

## Route
- Namespace: `engineering`
- Namespace Name: `Engineering.fyi`
- Route Path: `/tag/:tag`
- Route Name: `Tag`
- Example: `/engineering/tag/javascript`
- URL: `engineering.fyi`
- Language: `en`
- Categories: `programming`
- Maintainers: `suhang-only`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/engineering/tag.ts')`

## Description
| JSON    | Javascript     | Java | Apache | AWS | SQL | React | Golang    |
| ---- | ---------- | ---- | ------ | --- | --- | ----- | ------ |
| json | javascript | java | apache | aws | sql | react | golang |

## Parameters
- `tag`: Browse programming languages, frameworks, and technologies


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `engineering.fyi/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| JSON    | Javascript     | Java | Apache | AWS | SQL | React | Golang    |\n| ---- | ---------- | ---- | ------ | --- | --- | ----- | ------ |\n| json | javascript | java | apache | aws | sql | react | golang |",
  "example": "/engineering/tag/javascript",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "suhang-only"
  ],
  "module": "() => import('@/routes/engineering/tag.ts')",
  "name": "Tag",
  "parameters": {
    "tag": "Browse programming languages, frameworks, and technologies"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "engineering.fyi/tag/:tag"
      ]
    }
  ]
}
```
