# Android Mods

Неофициальные модифицированные APK для маркетплейсов.

> **Важно.** Моды не связаны с правообладателями приложений. Установка только на свой риск: возможны баны аккаунта, нестабильность, проблемы с обновлениями. Скачивайте APK только из [Releases](../../releases) этого репозитория.

Поддерживаемые ABI: **arm64-v8a** (большинство устройств) и **armeabi-v7a** (старые 32-bit).

---

## Wildberries

<p>
  <img src="assets/icons/wildberries.png" alt="Wildberries" width="72" height="72" align="left" style="margin-right:16px" />
  <strong>Wildberries</strong><br />
  Версия мода: <code>7.8.4001</code><br />
  Варианты: обычный · black (AMOLED) · клон
</p>

<br clear="all" />

<details>
<summary><strong>Что изменено</strong></summary>

- Отключены баннеры (главная, профиль, SuperApp-карусель)
- Отключён розыгрыш / raffle-информер
- Отключена аналитика (`WBAnalytics`)
- GMS / Play Services проверки обнулены
- Signature killer
- `versionCode` завышен
- Чистка лишних ресурсов (оставлен xxhdpi)
- **Black:** AMOLED-тема (`#000000`)
- **Клон:** отдельный `applicationId`

</details>

<details>
<summary><strong>Загрузки (GitHub Releases)</strong></summary>


| Вариант | arm64-v8a | armeabi-v7a |
|---------|-----------|-------------|
| Обычный | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/wb-7.8.4001/wildberries_7.8.4001_mod_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/wb-7.8.4001/wildberries_7.8.4001_mod_armeabi-v7a.apk) |
| Black | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/wb-7.8.4001/wildberries_7.8.4001_black_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/wb-7.8.4001/wildberries_7.8.4001_black_armeabi-v7a.apk) |
| Клон | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/wb-7.8.4001/wildberries_7.8.4001_clone_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/wb-7.8.4001/wildberries_7.8.4001_clone_armeabi-v7a.apk) |

Все ассеты тега: [wb-7.8.4001](https://github.com/pabushabi/pabushabi_mods/releases/tag/wb-7.8.4001)

</details>

---

## Avito

<p>
  <img src="assets/icons/avito.png" alt="Avito" width="72" height="72" align="left" style="margin-right:16px" />
  <strong>Avito</strong><br />
  Версия мода: <code>235.1</code><br />
  Варианты: обычный · black (AMOLED) · клон
</p>

<br clear="all" />

<details>
<summary><strong>Что изменено</strong></summary>

- Отключена реклама (layouts + `loadAd` / native ad)
- Убраны пустые чёрные блоки после скрытия рекламы
- Отключена аналитика (AppMetrica / Adjust / GMS / Firebase → localhost)
- Скрыта карусель сторисов
- Скрыта карусель «Видео для вас»
- Плашки заголовка в один ряд
- Скрыта кнопка Ави ИИ
- Скрыты mini menu / короткие видео
- Скрыт «Портал призов» в профиле
- Скрыт блок «Может быть интересно»
- Убраны всплывающие bottom sheets при запуске (force update, beduin, уведомления)
- Оптимизация графики (xxhdpi), сжатие dex
- Signature killer, завышенный `versionCode`
- **Black:** AMOLED-тема (`#000000`)
- **Клон:** `com.avito.android.clone` рядом со стоком

</details>

<details>
<summary><strong>Загрузки (GitHub Releases)</strong></summary>


| Вариант | arm64-v8a | armeabi-v7a |
|---------|-----------|-------------|
| Обычный | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/avito-235.1/avito_235.1_mod_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/avito-235.1/avito_235.1_mod_armeabi-v7a.apk) |
| Black | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/avito-235.1/avito_235.1_black_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/avito-235.1/avito_235.1_black_armeabi-v7a.apk) |
| Клон | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/avito-235.1/avito_235.1_clone_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/avito-235.1/avito_235.1_clone_armeabi-v7a.apk) |

Все ассеты тега: [avito-235.1](https://github.com/pabushabi/pabushabi_mods/releases/tag/avito-235.1)

</details>


---

## Установка

1. Включите установку из неизвестных источников для браузера / файлового менеджера.
2. Скачайте APK под ваш ABI (`arm64-v8a` — почти всегда он).
3. Установите. Поверх стокового приложения не встанет - удалите сток **или** берите вариант «клон» (где есть).
4. Обновления мода встанут только на мои моды.

---


## Дисклеймер

Проект образовательный / для личного использования. Автор не несёт ответственности за последствия установки. Не распространяйте APK от третьих лиц под видом релизов этого репозитория.
