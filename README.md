# Мои приложения, созданные с помощью ИИ

Репозиторий с собранными приложениями, разработанными при участии ИИ. Скачивайте и устанавливайте APK прямо с этой страницы.

## Izorgram (Telegram-клиент)

Продвинутый клиент Telegram на базе форка Goregram (бренд `izorgram`, пакет `com.amanoteam.flonne`).

### Что внутри
- Релизная сборка без крэша и зависаний: исправлена ошибка данных `Integer → Long` (`proxy_dialog`), добавлена автоматическая миграция.
- ART-baseline profile — быстрый запуск и плавный интерфейс.
- Встроенный набор для системного VPN (движок Xray-core + tun2socks через `libgojni.so`) — код интегрирован, UI упрощён.
- Одна поддерживаемая архитектура: `arm64-v8a` (Android 8+, 64-бит).

### Установка
1. Скачайте `Izorgram-release.apk`.
2. В настройках телефона включите «Установка из неизвестных источников».
3. Откройте файл и нажмите «Установить».

### Файлы
| Файл | Описание | Версия |
|---|---|---|
| `Izorgram-release.apk` | Релизная сборка | 12.10.1 (v70389) |

### Сборка из исходников
Исходники: [Izorgram-Sources](https://github.com/avirbeta/Izorgram-Sources) — форк [Goregram](https://github.com/AmanoTeam/Goregram).

```
./gradlew :TMessagesProj_App:assembleAfatRelease
```
APK появится в `TMessagesProj_App/build/outputs/apk/afat/release/app.apk`.

## Лицензия
Используемый код основан на открытых проектах Telegram и Goregram.