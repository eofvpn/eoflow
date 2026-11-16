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
| Android | Любые смартфоны, планшеты и Android TV, Android 8.0+ | 6.1.14 (сборка 6036) | [EOFLOW-6.1.14-android-universal.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.14/EOFLOW-6.1.14-android-universal.apk) |
| Android | 64-битный процессор ARM (ARM64): большинство современных смартфонов, планшетов и телевизоров | 6.1.14 (сборка 6036) | [EOFLOW-6.1.14-android-arm64-v8a.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.14/EOFLOW-6.1.14-android-arm64-v8a.apk) |
| Android | 32-битный процессор ARM (ARMv7): старые и бюджетные смартфоны и TV-приставки | 6.1.14 (сборка 6036) | [EOFLOW-6.1.14-android-armeabi-v7a.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.14/EOFLOW-6.1.14-android-armeabi-v7a.apk) |
| Android | Процессор x86_64 (Intel/AMD): Chromebook, эмуляторы, некоторые планшеты и приставки | 6.1.14 (сборка 6036) | [EOFLOW-6.1.14-android-x86_64.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.14/EOFLOW-6.1.14-android-x86_64.apk) |
| Windows | Компьютеры и ноутбуки | 6.1.11 | [EOFLOW-6.1.11-windows-setup.exe](https://github.com/eofvpn/eoflow/releases/download/windows-v6.1.11/EOFLOW-6.1.11-windows-setup.exe) |
| Linux | Ubuntu 24.04+ и Debian 13+, процессоры Intel/AMD (x86_64) | 6.1.14 (сборка 6036) | [EOFLOW-6.1.14-linux-amd64.deb](https://github.com/eofvpn/eoflow/releases/download/linux-v6.1.14/EOFLOW-6.1.14-linux-amd64.deb) |
| Linux | Ubuntu 24.04+ и Debian 13+, процессоры ARM64 | 6.1.14 (сборка 6036) | [EOFLOW-6.1.14-linux-arm64.deb](https://github.com/eofvpn/eoflow/releases/download/linux-v6.1.14/EOFLOW-6.1.14-linux-arm64.deb) |

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
sudo apt install ./EOFLOW-6.1.14-linux-amd64.deb
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
| EOFLOW-6.1.14-android-universal.apk | `d42b36742d41092787a53f4f6dd2066516e8db3bb3e7a76bb52f11a4991dc343` |
| EOFLOW-6.1.14-android-arm64-v8a.apk | `b7d78e28fb61c6e51d581c1b8d67ad94d81ef0a068d400b84328e81e15390ad0` |
| EOFLOW-6.1.14-android-armeabi-v7a.apk | `7a7336a38b7775bea71c7d115440bc260ab0030c211f9b27af734fd9f44b09d0` |
| EOFLOW-6.1.14-android-x86_64.apk | `e08805339f2c63dddade03926c01b19c0922e63aee14838ebab84206f397cdc8` |
| EOFLOW-6.1.11-windows-setup.exe | `806f484833c5b747d99eaff5ac105f4760d2b371e5669c3585df2296cf48a3dd` |
| EOFLOW-6.1.14-linux-amd64.deb | `1ec10b98e2e59e616d0bcd227c2fee4c1baead0b33d0f7150a2d3421885718c3` |
| EOFLOW-6.1.14-linux-arm64.deb | `e527884313b4661fc7ce9511109fdfadaa5f8e2d17fb9caf5d24b91b341ef0b2` |

Проверить сумму скачанного файла:

- macOS / Linux: `shasum -a 256 <файл>`
- Windows (PowerShell): `Get-FileHash <файл> -Algorithm SHA256`

Скачивайте EOFLOW только из этого репозитория, с сайта [eofvpn.app](https://eofvpn.app) или из официальных магазинов приложений.
