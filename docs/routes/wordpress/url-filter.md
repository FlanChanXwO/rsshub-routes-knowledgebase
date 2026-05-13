# WordPress - WordPress

## Coverage
`index-only`

## Route
- Namespace: `wordpress`
- Namespace Name: `WordPress`
- Route Path: `/:url?/:filter{.+}?`
- Route Name: `WordPress`
- Example: `/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast`
- URL: `wordpress.org`
- Language: `en`
- Categories: `blog`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/wordpress/index.ts')`

## Description
If you subscribe to [WordPress News](https://wordpress.org/news/)，where the URL is `https://wordpress.org/news/`, Encode the URL using `encodeURIComponent()` and then use it as the parameter. Therefore, the route will be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews).

::: tip
  If you wish to subscribe to specific categories or tags, you can fill in the "filter" parameter in the route. `/category/Podcast` to subscribe to the Podcast category. In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast).

  You can also subscribe to multiple categories. `/category/Podcast,Community` to subscribe to both the Podcast and Community categories. In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast,Community`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast,Community).

  Categories and tags can be combined as well. `/category/Releases/tag/tagging` to subscribe to the Releases category and the tagging tag. In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Releases/tag/tagging`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Releases/tag/tagging).
  
  You can also search for keywords. `/search/Blog` to search for the keyword "Blog". In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/search/Blog`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/search/Blog).
:::

## Parameters
- `url`: URL, <https://wordpress.org/news> by default
- `filter`: Filter, see below


## Features
- `requireConfig`: [{"description": "This RSS is disabled unless 'ALLOW_USER_SUPPLY_UNSAFE_DOMAIN' is set to 'true'.", "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN", "optional": false}]
- `requirePuppeteer`: false
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
    "blog"
  ],
  "description": "If you subscribe to [WordPress News](https://wordpress.org/news/)，where the URL is `https://wordpress.org/news/`, Encode the URL using `encodeURIComponent()` and then use it as the parameter. Therefore, the route will be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews).\n\n::: tip\n  If you wish to subscribe to specific categories or tags, you can fill in the \"filter\" parameter in the route. `/category/Podcast` to subscribe to the Podcast category. In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast).\n\n  You can also subscribe to multiple categories. `/category/Podcast,Community` to subscribe to both the Podcast and Community categories. In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast,Community`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast,Community).\n\n  Categories and tags can be combined as well. `/category/Releases/tag/tagging` to subscribe to the Releases category and the tagging tag. In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Releases/tag/tagging`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Releases/tag/tagging).\n  \n  You can also search for keywords. `/search/Blog` to search for the keyword \"Blog\". In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/search/Blog`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/search/Blog).\n:::",
  "example": "/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "This RSS is disabled unless 'ALLOW_USER_SUPPLY_UNSAFE_DOMAIN' is set to 'true'.",
        "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN",
        "optional": false
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/wordpress/index.ts')",
  "name": "WordPress",
  "parameters": {
    "filter": "Filter, see below",
    "url": "URL, <https://wordpress.org/news> by default"
  },
  "path": "/:url?/:filter{.+}?",
  "radar": [],
  "url": "wordpress.org"
}
```
