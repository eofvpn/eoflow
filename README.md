# EOFLOW — официальные сборки приложения

Официальные установочные файлы приложения **EOFLOW** от **EOF. SOLUTIONS LLC**.

Сайт: [eofvpn.app](https://eofvpn.app) · Поддержка: [user@eof.support](mailto:user@eof.support) · Telegram: [@eofvpncc](https://t.me/eofvpncc)

Все файлы публикуются только в разделе [Releases](https://github.com/eofvpn/eoflow/releases). Релизы разделены по платформам:

- `android-vX.Y.Z` — Android и Android TV;
- `windows-vX.Y.Z` — Windows.

## Актуальные версии

| Платформа | Устройства | Версия | Файл |
|---|---|---|---|
| Android | Смартфоны и планшеты, Android 8.0+ | 6.1.5 (сборка 6012) | [EOFLOW-6.1.5-android-universal.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.5/EOFLOW-6.1.5-android-universal.apk) |
| Android TV | Телевизоры и приставки с 64-битным процессором (ARM64), Android 8.0+ | 6.1.5 (сборка 6012) | [EOFLOW-6.1.5-android-tv-arm64-v8a.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.5/EOFLOW-6.1.5-android-tv-arm64-v8a.apk) |
| Android TV | Телевизоры и приставки с 32-битным процессором (ARMv7), Android 8.0+ | 6.1.5 (сборка 6012) | [EOFLOW-6.1.5-android-tv-armeabi-v7a.apk](https://github.com/eofvpn/eoflow/releases/download/android-v6.1.5/EOFLOW-6.1.5-android-tv-armeabi-v7a.apk) |
| Windows | Компьютеры и ноутбуки | 6.1.0 | [EOFLOW-6.1.0-windows-setup.exe](https://github.com/eofvpn/eoflow/releases/download/windows-v6.1.0/EOFLOW-6.1.0-windows-setup.exe) |

## Android

**Какой файл выбрать**

- `EOFLOW-…-android-universal.apk` — универсальная сборка: подходит для любых смартфонов, планшетов и приставок (ARM64, ARMv7, x86_64). Если не уверены — берите её.
- `EOFLOW-…-android-tv-arm64-v8a.apk` — облегчённая сборка для Android TV с 64-битным процессором. Подходит большинству современных телевизоров и приставок.
- `EOFLOW-…-android-tv-armeabi-v7a.apk` — облегчённая сборка для Android TV с 32-битным процессором: старые и бюджетные приставки. Если 64-битная TV-сборка не устанавливается — попробуйте эту.
- Если ни одна TV-сборка не подходит — используйте универсальную.

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

Контрольные суммы SHA-256 файлов:

| Файл | SHA-256 |
|---|---|
| EOFLOW-6.1.5-android-universal.apk | `23a5b8aa653522425cae5adef038a08ca87d753239c8058eb27f5069ac07bdc0` |
| EOFLOW-6.1.5-android-tv-arm64-v8a.apk | `485b14b2f924383f82af400acb60889518a3125e34e2074fb2f2b3dacaa629c5` |
| EOFLOW-6.1.5-android-tv-armeabi-v7a.apk | `59edd155aa2f265334a004a4c77dfccac047a9856da2768538a82767a9199779` |
| EOFLOW-6.1.0-windows-setup.exe | `7285f3b086d0af3625101a9647c74115094d753e831eea3e6742aca20429ca5a` |

Проверить сумму скачанного файла:

- macOS / Linux: `shasum -a 256 <файл>`
- Windows (PowerShell): `Get-FileHash <файл> -Algorithm SHA256`

Скачивайте EOFLOW только из этого репозитория, с сайта [eofvpn.app](https://eofvpn.app) или из официальных магазинов приложений.
