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
| Android | Любые смартфоны, планшеты и Android TV, Android 8.0+ | 6.1.15 (сборка 6039) | [EOFLOW-6.1.15-android-universal.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.15/EOFLOW-6.1.15-android-universal.apk) |
| Android | 64-битный процессор ARM (ARM64): большинство современных смартфонов, планшетов и телевизоров | 6.1.15 (сборка 6039) | [EOFLOW-6.1.15-android-arm64-v8a.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.15/EOFLOW-6.1.15-android-arm64-v8a.apk) |
| Android | 32-битный процессор ARM (ARMv7): старые и бюджетные смартфоны и TV-приставки | 6.1.15 (сборка 6039) | [EOFLOW-6.1.15-android-armeabi-v7a.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.15/EOFLOW-6.1.15-android-armeabi-v7a.apk) |
| Android | Процессор x86_64 (Intel/AMD): Chromebook, эмуляторы, некоторые планшеты и приставки | 6.1.15 (сборка 6039) | [EOFLOW-6.1.15-android-x86_64.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.15/EOFLOW-6.1.15-android-x86_64.apk) |
| Windows | Компьютеры и ноутбуки | 6.1.15 | [EOFLOW-6.1.15-windows-setup.exe](https://github.com/eofvpn/eoflow/releases/download/windows-v6.1.15/EOFLOW-6.1.15-windows-setup.exe) |
| Linux | Ubuntu 24.04+ и Debian 13+, процессоры Intel/AMD (x86_64) | 6.1.15 (сборка 6038) | [EOFLOW-6.1.15-linux-amd64.deb](https://github.com/eofvpn/eoflow/releases/download/linux-v6.1.15/EOFLOW-6.1.15-linux-amd64.deb) |
| Linux | Ubuntu 24.04+ и Debian 13+, процессоры ARM64 | 6.1.15 (сборка 6038) | [EOFLOW-6.1.15-linux-arm64.deb](https://github.com/eofvpn/eoflow/releases/download/linux-v6.1.15/EOFLOW-6.1.15-linux-arm64.deb) |

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
sudo apt install ./EOFLOW-6.1.15-linux-amd64.deb
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
| EOFLOW-6.1.15-android-universal.apk | `c083a717b81956e9b32fe278ca49aeb39b5e89e1ba501a34fc551e4809c1795a` |
| EOFLOW-6.1.15-android-arm64-v8a.apk | `e925ad70b5e2c6115dcf4c32cf4c811d5efd2465124fb4c35b22c43603f032c0` |
| EOFLOW-6.1.15-android-armeabi-v7a.apk | `95deec13aec65b4d2693fcc29d2c5bdaa6b3c11409b8f9c64db5cc7a3d1e78eb` |
| EOFLOW-6.1.15-android-x86_64.apk | `85b55cac0ba0e9f269ad496200f2db764f86fc5a459dbabcd812cf13243d28d7` |
| EOFLOW-6.1.15-windows-setup.exe | `523abbda6bda34ccf472fa1a93ed9e66585dbdb1ff9c87ae5f0f8060712daeda` |
| EOFLOW-6.1.15-linux-amd64.deb | `4b2fffe48bed7ac529396bb8e371bc599865bda6b428f92c1d55c2da526c054d` |
| EOFLOW-6.1.15-linux-arm64.deb | `f78a8e3b1f883d3d1024dff8085011fad320868eed6d34b72e8d4ad986248b23` |

Проверить сумму скачанного файла:

- macOS / Linux: `shasum -a 256 <файл>`
- Windows (PowerShell): `Get-FileHash <файл> -Algorithm SHA256`

Скачивайте EOFLOW только из этого репозитория, с сайта [eofvpn.app](https://eofvpn.app) или из официальных магазинов приложений.
