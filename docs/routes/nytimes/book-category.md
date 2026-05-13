# The New York Times - Best Seller Books

## Coverage
`index-only`

## Route
- Namespace: `nytimes`
- Namespace Name: `The New York Times`
- Route Path: `/book/:category?`
- Route Name: `Best Seller Books`
- Example: `/nytimes/book/combined-print-and-e-book-nonfiction`
- URL: `nytimes.com/`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `melvinto, pseudoyu`
- Source Location: `book.ts`
- Source Module: `() => import('@/routes/nytimes/book.ts')`

## Description
_None_

## Parameters
- `category`: {"default": "combined-print-and-e-book-nonfiction", "description": "Category, can be found on the [official page](https://www.nytimes.com/books/best-sellers/)", "options": [{"label": "Combined Print & E-Book Nonfiction", "value": "combined-print-and-e-book-nonfiction"}, {"label": "Hardcover Nonfiction", "value": "hardcover-nonfiction"}, {"label": "Paperback Nonfiction", "value": "paperback-nonfiction"}, {"label": "Advice, How-To & Miscellaneous", "value": "advice-how-to-and-miscellaneous"}, {"label": "Combined Print & E-Book Fiction", "value": "combined-print-and-e-book-fiction"}, {"label": "Hardcover Fiction", "value": "hardcover-fiction"}, {"label": "Paperback Trade Fiction", "value": "trade-fiction-paperback"}, {"label": "Children's Middle Grade Hardcover", "value": "childrens-middle-grade-hardcover"}, {"label": "Picture Books", "value": "picture-books"}, {"label": "Series Books", "value": "series-books"}, {"label": "Young Adult Hardcover", "value": "young-adult-hardcover"}]}


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
  - `nytimes.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/nytimes/book/combined-print-and-e-book-nonfiction",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "book.ts",
  "maintainers": [
    "melvinto",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/nytimes/book.ts')",
  "name": "Best Seller Books",
  "parameters": {
    "category": {
      "default": "combined-print-and-e-book-nonfiction",
      "description": "Category, can be found on the [official page](https://www.nytimes.com/books/best-sellers/)",
      "options": [
        {
          "label": "Combined Print & E-Book Nonfiction",
          "value": "combined-print-and-e-book-nonfiction"
        },
        {
          "label": "Hardcover Nonfiction",
          "value": "hardcover-nonfiction"
        },
        {
          "label": "Paperback Nonfiction",
          "value": "paperback-nonfiction"
        },
        {
          "label": "Advice, How-To & Miscellaneous",
          "value": "advice-how-to-and-miscellaneous"
        },
        {
          "label": "Combined Print & E-Book Fiction",
          "value": "combined-print-and-e-book-fiction"
        },
        {
          "label": "Hardcover Fiction",
          "value": "hardcover-fiction"
        },
        {
          "label": "Paperback Trade Fiction",
          "value": "trade-fiction-paperback"
        },
        {
          "label": "Children's Middle Grade Hardcover",
          "value": "childrens-middle-grade-hardcover"
        },
        {
          "label": "Picture Books",
          "value": "picture-books"
        },
        {
          "label": "Series Books",
          "value": "series-books"
        },
        {
          "label": "Young Adult Hardcover",
          "value": "young-adult-hardcover"
        }
      ]
    }
  },
  "path": "/book/:category?",
  "radar": [
    {
      "source": [
        "nytimes.com/"
      ],
      "target": ""
    }
  ],
  "url": "nytimes.com/",
  "view": 5
}
```
