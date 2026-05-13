# 中央气象台 Route Index

## Namespace
- Namespace: `nmc`
- Display Name: `中央气象台`
- URL: `nmc.cn`
- Language: `_None_`
- Aliases: `nmc, nmc.cn, 中央气象台`
- Route Count: `2`

## Routes

### 产品
- Route ID: `nmc:/nmc/publish/:id{.+}?`
- Route Path: `/nmc/publish/:id{.+}?`
- File: `docs/routes/nmc/nmc-publish-id.md`
- File Name: `nmc-publish-id.md`
- Categories: `forecast`
- Maintainers: `nczitzk`

### 全国气象预警
- Route ID: `nmc:/nmc/weatheralarm/:province?`
- Route Path: `/nmc/weatheralarm/:province?`
- File: `docs/routes/nmc/nmc-weatheralarm-province.md`
- File Name: `nmc-weatheralarm-province.md`
- Categories: `forecast`
- Maintainers: `ylc395`
