# LinkedIn - Company Posts

## Coverage
`index-only`

## Route
- Namespace: `linkedin`
- Namespace Name: `LinkedIn`
- Route Path: `/company/:company_id/posts`
- Route Name: `Company Posts`
- Example: `/linkedin/company/google/posts`
- URL: `linkedin.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `saifazmi`
- Source Location: `posts.ts`
- Source Module: `() => import('@/routes/linkedin/posts.ts')`

## Description
Get company's LinkedIn posts by company ID

## Parameters
- `company_id`: Company's LinkedIn profile ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportRadar`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "Get company's LinkedIn posts by company ID",
  "example": "/linkedin/company/google/posts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": false,
    "supportScihub": false
  },
  "location": "posts.ts",
  "maintainers": [
    "saifazmi"
  ],
  "module": "() => import('@/routes/linkedin/posts.ts')",
  "name": "Company Posts",
  "parameters": {
    "company_id": "Company's LinkedIn profile ID"
  },
  "path": "/company/:company_id/posts"
}
```
