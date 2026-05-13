# TechCrunch - Category

## Coverage
`index-only`

## Route
- Namespace: `techcrunch`
- Namespace Name: `TechCrunch`
- Route Path: `/techcrunch/category/:categoryId`
- Route Name: `Category`
- Example: `/techcrunch/category/577047203`
- URL: `techcrunch.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `MilliumOrion`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
Use the category ID to retrieve a list of articles, category ID.\
From the page source of `https://techcrunch.com/category/***`, locate the `{category_id}`\
Example:\
`html` -> `head` -> `<link rel="alternate" title="JSON" type="application/json" href="https://techcrunch.com/wp-json/wp/v2/categories/{category_id}">`

## Parameters
- `categoryId`: 分类id


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Use the category ID to retrieve a list of articles, category ID.\\\nFrom the page source of `https://techcrunch.com/category/***`, locate the `{category_id}`\\\nExample:\\\n`html` -> `head` -> `<link rel=\"alternate\" title=\"JSON\" type=\"application/json\" href=\"https://techcrunch.com/wp-json/wp/v2/categories/{category_id}\">`",
  "example": "/techcrunch/category/577047203",
  "heat": 1,
  "location": "category.ts",
  "maintainers": [
    "MilliumOrion"
  ],
  "name": "Category",
  "parameters": {
    "categoryId": "分类id"
  },
  "path": "/category/:categoryId",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
