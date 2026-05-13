# AP News Route Index

## Namespace
- Namespace: `apnews`
- Display Name: `AP News`
- URL: `apnews.com`
- Language: `_None_`
- Aliases: `ap news, apnews, apnews.com`
- Route Count: `4`

## Routes

### News (from mobile client API)
- Route ID: `apnews:/apnews/mobile/:path{.+}?`
- Route Path: `/apnews/mobile/:path{.+}?`
- File: `docs/routes/apnews/apnews-mobile-path.md`
- File Name: `apnews-mobile-path.md`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`

### News
- Route ID: `apnews:/apnews/rss/:category?`
- Route Path: `/apnews/rss/:category?`
- File: `docs/routes/apnews/apnews-rss-category.md`
- File Name: `apnews-rss-category.md`
- Categories: `traditional-media`
- Maintainers: `zoenglinghou, mjysci, TonyRL`

### Sitemap
- Route ID: `apnews:/apnews/sitemap/:route`
- Route Path: `/apnews/sitemap/:route`
- File: `docs/routes/apnews/apnews-sitemap-route.md`
- File Name: `apnews-sitemap-route.md`
- Categories: `traditional-media`
- Maintainers: `zoenglinghou, mjysci, TonyRL, dzx-dzx`

### Topics
- Route ID: `apnews:/apnews/topics/:topic?`
- Route Path: `/apnews/topics/:topic?`
- File: `docs/routes/apnews/apnews-topics-topic.md`
- File Name: `apnews-topics-topic.md`
- Categories: `traditional-media`
- Maintainers: `zoenglinghou, mjysci, TonyRL`
