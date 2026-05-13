# 央视新闻 Route Index

## Namespace
- Namespace: `cctv`
- Display Name: `央视新闻`
- URL: `news.cctv.com`
- Language: `zh-CN`
- Aliases: `cctv, news, news.cctv.com, 央视新闻`
- Route Count: `4`

## Routes

### 专题
- Route ID: `cctv:/:category`
- Route Path: `/:category`
- File: `docs/routes/cctv/category.md`
- File Name: `category.md`
- Categories: `traditional-media`
- Maintainers: `idealclover, xyqfer`

### 新闻联播
- Route ID: `cctv:/:site/:category/:name`
- Route Path: `/:site/:category/:name`
- File: `docs/routes/cctv/site-category-name.md`
- File Name: `site-category-name.md`
- Categories: `traditional-media`
- Maintainers: `zengxs`

### 栏目
- Route ID: `cctv:/lm/:id?`
- Route Path: `/lm/:id?`
- File: `docs/routes/cctv/lm-id.md`
- File Name: `lm-id.md`
- Categories: `traditional-media`
- Maintainers: `nczitzk`

### 央视网图片《镜象》
- Route ID: `cctv:/photo/jx`
- Route Path: `/photo/jx`
- File: `docs/routes/cctv/photo-jx.md`
- File Name: `photo-jx.md`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
