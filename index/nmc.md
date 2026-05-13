# 中央气象台 Route Index

## Namespace
- Namespace: `nmc`
- Display Name: `中央气象台`
- URL: `nmc.cn`
- Language: `zh-CN`
- Aliases: `nmc, nmc.cn, 中央气象台`
- Route Count: `2`

## Routes

### 产品
- Route ID: `nmc:/publish/:id{.+}?`
- Route Path: `/publish/:id{.+}?`
- File: `docs/routes/nmc/publish-id.md`
- File Name: `publish-id.md`
- Categories: `forecast`
- Maintainers: `nczitzk`

### 全国气象预警
- Route ID: `nmc:/weatheralarm/:province?`
- Route Path: `/weatheralarm/:province?`
- File: `docs/routes/nmc/weatheralarm-province.md`
- File Name: `weatheralarm-province.md`
- Categories: `forecast`
- Maintainers: `ylc395`
