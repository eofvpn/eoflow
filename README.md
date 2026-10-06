# EOFLOW — официальные сборки приложения

Официальные установочные файлы приложения **EOFLOW** от **EOF YOMI LABS LTD**.

Сайт: [eofvpn.app](https://eofvpn.app) · Поддержка: [user@eof.support](mailto:user@eof.support) · Telegram: [@eofvpncc](https://t.me/eofvpncc)

Все файлы публикуются только в разделе [Releases](https://github.com/eofvpn/eoflow/releases). Релизы разделены по платформам:

- `android-vX.Y.Z` — Android и Android TV;
- `windows-vX.Y.Z` — Windows.

## Актуальные версии

| Платформа | Устройства | Версия | Файл |
|---|---|---|---|
| Android | Любые смартфоны, планшеты и Android TV, Android 8.0+ | 6.1.7 (сборка 6014) | [EOFLOW-6.1.7-android-universal.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.7/EOFLOW-6.1.7-android-universal.apk) |
| Android | 64-битный процессор ARM (ARM64): большинство современных смартфонов, планшетов и телевизоров | 6.1.7 (сборка 6014) | [EOFLOW-6.1.7-android-arm64-v8a.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.7/EOFLOW-6.1.7-android-arm64-v8a.apk) |
| Android | 32-битный процессор ARM (ARMv7): старые и бюджетные смартфоны и TV-приставки | 6.1.7 (сборка 6014) | [EOFLOW-6.1.7-android-armeabi-v7a.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.7/EOFLOW-6.1.7-android-armeabi-v7a.apk) |
| Android | Процессор x86_64 (Intel/AMD): Chromebook, эмуляторы, некоторые планшеты и приставки | 6.1.7 (сборка 6014) | [EOFLOW-6.1.7-android-x86_64.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.7/EOFLOW-6.1.7-android-x86_64.apk) |
| Windows | Компьютеры и ноутбуки | 6.1.7 | [EOFLOW-6.1.7-windows-setup.exe](https://github.com/eofvpn/eoflow/releases/download/windows-v6.1.7/EOFLOW-6.1.7-windows-setup.exe) |

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
| EOFLOW-6.1.7-android-universal.apk | `ffd58ec567900dc1e0ce1d3cdae596b9da9d3d1e83fa4381a32f0a346d8dd26a` |
| EOFLOW-6.1.7-android-arm64-v8a.apk | `275af4552ce9d99ecaa70c800fe581575c54dfca2188719a22315408b3ba6688` |
| EOFLOW-6.1.7-android-armeabi-v7a.apk | `ba1ea27dd32ff0fc0e7d3dc5231225180fb6257205e6b9836dc5bf1f398c8a52` |
| EOFLOW-6.1.7-android-x86_64.apk | `a959fac23d737c6909d281185972aaf934d77c4320afee1d2bde1d790b10e566` |
| EOFLOW-6.1.7-windows-setup.exe | `9507f6232854dad2e1fcc23550316ae18328110f7e1e49459895c45d9bcbedfe` |

Проверить сумму скачанного файла:

- macOS / Linux: `shasum -a 256 <файл>`
- Windows (PowerShell): `Get-FileHash <файл> -Algorithm SHA256`

Скачивайте EOFLOW только из этого репозитория, с сайта [eofvpn.app](https://eofvpn.app) или из официальных магазинов приложений.
