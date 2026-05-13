# 深圳证券交易所 Route Index

## Namespace
- Namespace: `szse`
- Display Name: `深圳证券交易所`
- URL: `szse.cn`
- Language: `zh-CN`
- Aliases: `szse, szse.cn, 深圳证券交易所`
- Route Count: `5`

## Routes

### 上市公司公告
- Route ID: `szse:/disclosure/listed/notice/:query?`
- Route Path: `/disclosure/listed/notice/:query?`
- File: `docs/routes/szse/disclosure-listed-notice-query.md`
- File Name: `disclosure-listed-notice-query.md`
- Categories: `finance`
- Maintainers: `nczitzk`

### 问询函件
- Route ID: `szse:/inquire/:category?/:select?/:keyword?`
- Route Path: `/inquire/:category?/:select?/:keyword?`
- File: `docs/routes/szse/inquire-category-select-keyword.md`
- File Name: `inquire-category-select-keyword.md`
- Categories: `finance`
- Maintainers: `Jeason0228, nczitzk`

### 上市公告 - 可转换债券
- Route ID: `szse:/notice`
- Route Path: `/notice`
- File: `docs/routes/szse/notice.md`
- File Name: `notice.md`
- Categories: `finance`
- Maintainers: `Jeason0228, nczitzk`

### 创业板项目动态
- Route ID: `szse:/projectdynamic/:type?/:stage?/:status?`
- Route Path: `/projectdynamic/:type?/:stage?/:status?`
- File: `docs/routes/szse/projectdynamic-type-stage-status.md`
- File Name: `projectdynamic-type-stage-status.md`
- Categories: `finance`
- Maintainers: `nczitzk`

### 本所业务规则
- Route ID: `szse:/rule/:channel{.+}?`
- Route Path: `/rule/:channel{.+}?`
- File: `docs/routes/szse/rule-channel.md`
- File Name: `rule-channel.md`
- Categories: `finance`
- Maintainers: `nczitzk`
