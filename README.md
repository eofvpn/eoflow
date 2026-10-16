# EOFLOW — официальные сборки приложения

Официальные установочные файлы приложения **EOFLOW** от **EOF YOMI LABS LTD**.

Сайт: [eofvpn.app](https://eofvpn.app) · Поддержка: [user@eof.support](mailto:user@eof.support) · Telegram: [@eofvpncc](https://t.me/eofvpncc)

Все файлы публикуются только в разделе [Releases](https://github.com/eofvpn/eoflow/releases). Релизы разделены по платформам:

- `android-vX.Y.Z` — Android и Android TV;
- `windows-vX.Y.Z` — Windows;
- `linux-vX.Y.Z` — Linux (Ubuntu, Debian).

## Актуальные версии

| Платформа | Устройства | Версия | Файл |
|---|---|---|---|
| Android | Любые смартфоны, планшеты и Android TV, Android 8.0+ | 6.1.10 (сборка 6017) | [EOFLOW-6.1.10-android-universal.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.10/EOFLOW-6.1.10-android-universal.apk) |
| Android | 64-битный процессор ARM (ARM64): большинство современных смартфонов, планшетов и телевизоров | 6.1.10 (сборка 6017) | [EOFLOW-6.1.10-android-arm64-v8a.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.10/EOFLOW-6.1.10-android-arm64-v8a.apk) |
| Android | 32-битный процессор ARM (ARMv7): старые и бюджетные смартфоны и TV-приставки | 6.1.10 (сборка 6017) | [EOFLOW-6.1.10-android-armeabi-v7a.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.10/EOFLOW-6.1.10-android-armeabi-v7a.apk) |
| Android | Процессор x86_64 (Intel/AMD): Chromebook, эмуляторы, некоторые планшеты и приставки | 6.1.10 (сборка 6017) | [EOFLOW-6.1.10-android-x86_64.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.10/EOFLOW-6.1.10-android-x86_64.apk) |
| Windows | Компьютеры и ноутбуки | 6.1.10 | [EOFLOW-6.1.10-windows-setup.exe](https://github.com/eofvpn/eoflow/releases/download/windows-v6.1.10/EOFLOW-6.1.10-windows-setup.exe) |
| Linux | Ubuntu 24.04+ и Debian 13+, процессоры Intel/AMD (x86_64) | 6.1.10 (сборка 6017) | [EOFLOW-6.1.10-linux-amd64.deb](https://github.com/eofvpn/eoflow/releases/download/linux-v6.1.10/EOFLOW-6.1.10-linux-amd64.deb) |
| Linux | Ubuntu 24.04+ и Debian 13+, процессоры ARM64 | 6.1.10 (сборка 6017) | [EOFLOW-6.1.10-linux-arm64.deb](https://github.com/eofvpn/eoflow/releases/download/linux-v6.1.10/EOFLOW-6.1.10-linux-arm64.deb) |

Предыдущие версии доступны в разделе [Releases](https://github.com/eofvpn/eoflow/releases).

## Android

**Какой файл выбрать**

- `EOFLOW-…-android-universal.apk` — универсальная сборка для любого устройства. Если не уверены — берите её.
- `EOFLOW-…-android-arm64-v8a.apk` — облегчённая сборка для 64-битных процессоров ARM. Подходит большинству смартфонов, планшетов и телевизоров последних лет.
- `EOFLOW-…-android-armeabi-v7a.apk` — облегчённая сборка для 32-битных процессоров ARM: старые и бюджетные устройства. Если сборка ARM64 не устанавливается — попробуйте эту.
- `EOFLOW-…-android-x86_64.apk` — сборка для устройств на процессорах Intel и AMD.

Облегчённые сборки занимают примерно в три раза меньше места, чем универсальная.

**Android TV**

Все сборки работают на Android TV. Для большинства телевизоров и приставок подходит `arm64-v8a`. Если она не устанавливается — используйте `armeabi-v7a` или универсальную сборку.

**Установка из файла**

1. Скачайте APK на устройство.
2. Откройте файл и разрешите установку из этого источника, если система попросит.
3. Нажмите «Установить».

Приложение также доступно в магазинах:

- [Google Play](https://play.google.com/store/apps/details?id=cc.eofvpn.app)
- [Huawei AppGallery](https://appgallery.huawei.ru/app/C113896727)

## Windows

1. Скачайте `EOFLOW-…-windows-setup.exe`.
2. Запустите установщик и следуйте инструкциям.

## Linux

Пакеты .deb для Ubuntu 24.04+ и Debian 13+.

- `EOFLOW-…-linux-amd64.deb` — компьютеры и ноутбуки с процессорами Intel/AMD. Если не уверены — берите его.
- `EOFLOW-…-linux-arm64.deb` — устройства с 64-битным процессором ARM.

1. Скачайте пакет для своей архитектуры. Узнать её можно командой `dpkg --print-architecture`.
2. Установите его, находясь в папке с файлом:

```
sudo apt install ./EOFLOW-6.1.10-linux-amd64.deb
```

Недостающие зависимости apt установит сам.

## Проверка подлинности

Все Android-сборки подписаны одним сертификатом разработчика (идентификатор приложения `cc.eofvpn.app`):

```
SHA-256: 07:E5:C2:FA:BF:18:CA:FE:71:ED:6A:A5:A9:59:1C:57:BD:57:C0:A7:0E:40:42:86:55:EA:FA:55:8C:57:98:FA
```

Установщик для Windows подписан цифровой подписью компании **EOF YOMI LABS LTD** (сертификат выдан SSL.com). Проверить: правый клик по файлу → «Свойства» → «Цифровые подписи».

```
Отпечаток сертификата (SHA-1): E8F8C859814A60C3C6D513DF61A9D1895813E8C1
```

Контрольные суммы SHA-256 файлов:

| Файл | SHA-256 |
|---|---|
| EOFLOW-6.1.10-android-universal.apk | `0b7e97a1f38068068bd004193ecb343cbf9f0accb1f577108e6e1936067ab1cd` |
| EOFLOW-6.1.10-android-arm64-v8a.apk | `e986c32f64797fb45201ec20e4875c48c51c1e1b3052039b811ca78a74a106b2` |
| EOFLOW-6.1.10-android-armeabi-v7a.apk | `cb1bbd20534c161084532b544db03fd154b7b98f89b20f99cc10b6b87d3683a9` |
| EOFLOW-6.1.10-android-x86_64.apk | `94f167107f4bc7eeea5d314f883813bf19497af2c0968a6841d2ef456f319608` |
| EOFLOW-6.1.10-windows-setup.exe | `113807b36058bde6623f1987043b441eceba42c880ad474d6ead4711acfb5ae3` |
| EOFLOW-6.1.10-linux-amd64.deb | `be556e067c0a35d9bece835a23963ac3c57e57d455b685d3b7bba3ff1c5fd3cf` |
| EOFLOW-6.1.10-linux-arm64.deb | `9dbf96056461387078e2cfec57bdd72690cd1acecfd4ffd4eb3754ad218f4d0c` |

Проверить сумму скачанного файла:

- macOS / Linux: `shasum -a 256 <файл>`
- Windows (PowerShell): `Get-FileHash <файл> -Algorithm SHA256`

Скачивайте EOFLOW только из этого репозитория, с сайта [eofvpn.app](https://eofvpn.app) или из официальных магазинов приложений.
