# 人民网 Route Index

## Namespace
- Namespace: `people`
- Display Name: `人民网`
- URL: `people.com.cn`
- Language: `zh-CN`
- Aliases: `people, people.com.cn, 人民网`
- Route Count: `3`

## Routes

### 首页头条
- Route ID: `people:/:site?/:category{.+}?`
- Route Path: `/:site?/:category{.+}?`
- File: `docs/routes/people/site-category.md`
- File Name: `site-category.md`
- Categories: `None`
- Maintainers: `nczitzk, pseudoyu`

### 领导留言板
- Route ID: `people:/liuyan/:id/:state?`
- Route Path: `/liuyan/:id/:state?`
- File: `docs/routes/people/liuyan-id-state.md`
- File Name: `liuyan-id-state.md`
- Categories: `traditional-media`
- Maintainers: `nczitzk`

### 习近平系列重要讲话
- Route ID: `people:/xjpjh/:keyword?/:year?`
- Route Path: `/xjpjh/:keyword?/:year?`
- File: `docs/routes/people/xjpjh-keyword-year.md`
- File Name: `xjpjh-keyword-year.md`
- Categories: `traditional-media`
- Maintainers: `None`
