# Canada.ca - News by Department

## Coverage
`index-only`

## Route
- Namespace: `canada.ca`
- Namespace Name: `Canada.ca`
- Route Path: `/news/:lang/:department?`
- Route Name: `News by Department`
- Example: `/canada.ca/news/en/departmentfinance`
- URL: `www.canada.ca`
- Language: `en`
- Categories: `government`
- Maintainers: `elibroftw`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/canada.ca/news.ts')`

## Description
News from specific Canadian government departments

## Parameters
- `lang`: Language, en or fr
- `department`: dprtmnt query value


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
  - `www.canada.ca/:lang/department-finance.html`
  - `www.canada.ca/:lang/ministere-finances.html`
  - `www.canada.ca/:lang/department-finance/news/*`
  - `www.canada.ca/:lang/ministere-finances/nouvelles/*`
- `target`: `/news/:lang/departmentfinance`
### Rule 2
- `source`:
  - `ised-isde.canada.ca/site/ised/:lang`
  - `ised-isde.canada.ca/site/isde/:lang`
- `target`: `/news/:lang/departmentofindustry`
### Rule 3
- `source`:
  - `www.canada.ca/:lang/innovation-science-economic-development/news/*`
  - `www.canada.ca/:lang/innovation-sciences-developpement-economique/nouvelles/*`
- `target`: `/news/:lang/departmentofindustry`
### Rule 4
- `source`:
  - `www.canada.ca/:lang/news/advanced-news-search/news-results.html`
  - `www.canada.ca/:lang/nouvelles/recherche-avancee-de-nouvelles/resultats-de-nouvelles.html`
- `target`: `/news/:lang`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "News from specific Canadian government departments",
  "example": "/canada.ca/news/en/departmentfinance",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "elibroftw"
  ],
  "module": "() => import('@/routes/canada.ca/news.ts')",
  "name": "News by Department",
  "parameters": {
    "department": "dprtmnt query value",
    "lang": "Language, en or fr"
  },
  "path": "/news/:lang/:department?",
  "radar": [
    {
      "source": [
        "www.canada.ca/:lang/department-finance.html",
        "www.canada.ca/:lang/ministere-finances.html",
        "www.canada.ca/:lang/department-finance/news/*",
        "www.canada.ca/:lang/ministere-finances/nouvelles/*"
      ],
      "target": "/news/:lang/departmentfinance"
    },
    {
      "source": [
        "ised-isde.canada.ca/site/ised/:lang",
        "ised-isde.canada.ca/site/isde/:lang"
      ],
      "target": "/news/:lang/departmentofindustry"
    },
    {
      "source": [
        "www.canada.ca/:lang/innovation-science-economic-development/news/*",
        "www.canada.ca/:lang/innovation-sciences-developpement-economique/nouvelles/*"
      ],
      "target": "/news/:lang/departmentofindustry"
    },
    {
      "source": [
        "www.canada.ca/:lang/news/advanced-news-search/news-results.html",
        "www.canada.ca/:lang/nouvelles/recherche-avancee-de-nouvelles/resultats-de-nouvelles.html"
      ],
      "target": "/news/:lang"
    }
  ]
}
```
