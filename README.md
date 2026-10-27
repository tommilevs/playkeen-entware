# Playkeen Entware distribution

Public Entware packages for the closed Playkeen core. English is primary; Russian follows below.

## Install

```sh
curl -LfsS https://github.com/tommilevs/playkeen-entware/releases/download/v0.1.1/playkeen_0.1.1_all.ipk -o /tmp/playkeen.ipk
opkg install /tmp/playkeen.ipk
```

The package installs the POSIX CLI, WEB UI files, and an Entware init service on port `8787`. It requires the Entware `node` and `curl` packages.

## Русский

Публичные Entware-пакеты для закрытого ядра Playkeen.

Установка:

```sh
curl -LfsS https://github.com/tommilevs/playkeen-entware/releases/download/v0.1.1/playkeen_0.1.1_all.ipk -o /tmp/playkeen.ipk
opkg install /tmp/playkeen.ipk
```

Пакет устанавливает POSIX CLI, файлы WEB UI и init-сервис Entware на порту `8787`. Требуются пакеты Entware `node` и `curl`.
