# Notion - Database

## Coverage
`index-only`

## Route
- Namespace: `notion`
- Namespace Name: `Notion`
- Route Path: `/database/:databaseId`
- Route Name: `Database`
- Example: `/notion/database/a7cc133b68454f138011f1530a13531e`
- URL: `notion.so`
- Language: `en`
- Categories: `other`
- Maintainers: `curly210102`
- Source Location: `database.ts`
- Source Module: `() => import('@/routes/notion/database.ts')`

## Description
There is an optional query parameter called `properties=` that can be used to customize field mapping. There are three built-in fields: author, pubTime and link, which can be used to add additional information.

  For example, if you have set up three properties in your database - "Publish Time", "Author", and "Original Article Link" - then execute the following JavaScript code to get the result for the properties parameter.

  ```js
  encodeURIComponent(JSON.stringify({"pubTime": "Publish Time", "author": "Author", "link": "Original Article Link"}))
  ```

  There is an optional query parameter called `query=` that can be used to customize the search rules for your database, such as custom sorting and filtering rules.

  please refer to the [Notion API documentation](https://developers.notion.com/reference/post-database-query) and execute `encodeURIComponent(JSON.stringify(custom rules))` to provide the query parameter.

## Parameters
- `databaseId`: Database ID


## Features
- `requireConfig`: [{"description": "", "name": "NOTION_TOKEN"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `notion.so/:id`
- `target`: `/database/:id`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "There is an optional query parameter called `properties=` that can be used to customize field mapping. There are three built-in fields: author, pubTime and link, which can be used to add additional information.\n\n  For example, if you have set up three properties in your database - \"Publish Time\", \"Author\", and \"Original Article Link\" - then execute the following JavaScript code to get the result for the properties parameter.\n\n  ```js\n  encodeURIComponent(JSON.stringify({\"pubTime\": \"Publish Time\", \"author\": \"Author\", \"link\": \"Original Article Link\"}))\n  ```\n\n  There is an optional query parameter called `query=` that can be used to customize the search rules for your database, such as custom sorting and filtering rules.\n\n  please refer to the [Notion API documentation](https://developers.notion.com/reference/post-database-query) and execute `encodeURIComponent(JSON.stringify(custom rules))` to provide the query parameter.",
  "example": "/notion/database/a7cc133b68454f138011f1530a13531e",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "NOTION_TOKEN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "database.ts",
  "maintainers": [
    "curly210102"
  ],
  "module": "() => import('@/routes/notion/database.ts')",
  "name": "Database",
  "parameters": {
    "databaseId": "Database ID"
  },
  "path": "/database/:databaseId",
  "radar": [
    {
      "source": [
        "notion.so/:id"
      ],
      "target": "/database/:id"
    }
  ]
}
```
