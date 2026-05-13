# AP News Route Index

## Namespace
- Namespace: `apnews`
- Display Name: `AP News`
- URL: `apnews.com`
- Language: `en`
- Aliases: `ap news, apnews, apnews.com`
- Route Count: `5`

## Routes

### News (from mobile client API)
- Route ID: `apnews:/mobile/:path{.+}?`
- Route Path: `/mobile/:path{.+}?`
- File: `docs/routes/apnews/mobile-path.md`
- File Name: `mobile-path.md`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`

### Topics
- Route ID: `apnews:/nav/:nav{.*}?`
- Route Path: `/nav/:nav{.*}?`
- File: `docs/routes/apnews/nav-nav.md`
- File Name: `nav-nav.md`
- Categories: `traditional-media`
- Maintainers: `zoenglinghou, mjysci, TonyRL`

### News
- Route ID: `apnews:/rss/:category?`
- Route Path: `/rss/:category?`
- File: `docs/routes/apnews/rss-category.md`
- File Name: `rss-category.md`
- Categories: `traditional-media`
- Maintainers: `zoenglinghou, mjysci, TonyRL`

### Sitemap
- Route ID: `apnews:/sitemap/:route`
- Route Path: `/sitemap/:route`
- File: `docs/routes/apnews/sitemap-route.md`
- File Name: `sitemap-route.md`
- Categories: `traditional-media`
- Maintainers: `zoenglinghou, mjysci, TonyRL, dzx-dzx`

### Topics
- Route ID: `apnews:/topics/:topic?`
- Route Path: `/topics/:topic?`
- File: `docs/routes/apnews/topics-topic.md`
- File Name: `topics-topic.md`
- Categories: `traditional-media`
- Maintainers: `zoenglinghou, mjysci, TonyRL`
