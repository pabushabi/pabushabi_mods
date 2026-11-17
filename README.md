# Android Mods

Неофициальные модифицированные APK.

> **Важно.** Моды не связаны с правообладателями приложений. Установка только на свой риск: возможны баны аккаунта, нестабильность, проблемы с обновлениями. Скачивайте APK только из [Releases](../../releases) этого репозитория.

Поддерживаемые ABI: **arm64-v8a** (большинство устройств) и **armeabi-v7a** (старые 32-bit). Ozon и Дикси собраны только под arm64-v8a: в исходных бандлах нет 32-bit библиотек.

---

## Wildberries

<p>
  <img src="assets/icons/wildberries.png" alt="Wildberries" width="72" height="72" align="left" style="margin-right:16px" />
  <strong>Wildberries</strong><br />
  Версия мода: <code>7.8.6001</code><br />
  Варианты: обычный · black (AMOLED) · клон
</p>

<br clear="all" />

<details>
<summary><strong>Что изменено</strong></summary>

- Отключены баннеры (главная, профиль, SuperApp-карусель)
- Отключён розыгрыш / raffle-информер
- Отключена аналитика (`WBAnalytics`)
- GMS / Play Services проверки обнулены
- VPN-блокер выключен (оверлей / QR); fingerprint `VpnApps` уходит пустым
- Signature killer
- `versionCode` завышен
- Чистка лишних ресурсов (оставлен xxhdpi)
- **Black:** AMOLED-тема (`#000000`)
- **Клон:** `com.wildberries.ru.clone` + OnlyAuthSdk

</details>

<details>
<summary><strong>Загрузки (GitHub Releases)</strong></summary>


| Вариант | arm64-v8a | armeabi-v7a |
|---------|-----------|-------------|
| Обычный | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/wb-7.8.6001/wildberries_7.8.6001_mod_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/wb-7.8.6001/wildberries_7.8.6001_mod_armeabi-v7a.apk) |
| Black | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/wb-7.8.6001/wildberries_7.8.6001_black_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/wb-7.8.6001/wildberries_7.8.6001_black_armeabi-v7a.apk) |
| Клон | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/wb-7.8.6001/wildberries_7.8.6001_clone_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/wb-7.8.6001/wildberries_7.8.6001_clone_armeabi-v7a.apk) |

Все ассеты тега: [wb-7.8.6001](https://github.com/pabushabi/pabushabi_mods/releases/tag/wb-7.8.6001)

</details>

---

## Avito

<p>
  <img src="assets/icons/avito.png" alt="Avito" width="72" height="72" align="left" style="margin-right:16px" />
  <strong>Avito</strong><br />
  Версия мода: <code>237.5</code><br />
  Варианты: обычный · black (AMOLED) · клон
</p>

<br clear="all" />

<details>
<summary><strong>Что изменено</strong></summary>

- Отключена реклама (layouts + `loadAd` / native ad + skip SERP)
- Убраны пустые чёрные блоки после скрытия рекламы (hero hide без early return)
- Отключена аналитика (AppMetrica / Adjust / GMS / Crashlytics → localhost; FCM Installations жив)
- Скрыта карусель сторисов
- Плашки заголовка в один ряд
- Скрыта кнопка Ави ИИ
- Скрыты mini menu / короткие видео
- Скрыт «Портал призов» в профиле
- Скрыт блок «Может быть интересно»
- Убраны startup sheets (force update + onboarding; Beduin product sheets не трогаем)
- Оптимизация графики (xxhdpi), сжатие dex
- Signature killer, завышенный `versionCode`
- **Black:** AMOLED-тема (`#000000`)
- **Клон:** `com.avito.android.clone` рядом со стоком

</details>

<details>
<summary><strong>Загрузки (GitHub Releases)</strong></summary>


| Вариант | arm64-v8a | armeabi-v7a |
|---------|-----------|-------------|
| Обычный | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/avito-237.5/avito_237.5_mod_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/avito-237.5/avito_237.5_mod_armeabi-v7a.apk) |
| Black | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/avito-237.5/avito_237.5_black_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/avito-237.5/avito_237.5_black_armeabi-v7a.apk) |
| Клон | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/avito-237.5/avito_237.5_clone_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/avito-237.5/avito_237.5_clone_armeabi-v7a.apk) |

Все ассеты тега: [avito-237.5](https://github.com/pabushabi/pabushabi_mods/releases/tag/avito-237.5)

</details>

---

## Яндекс Маркет

<p>
  <strong>Яндекс Маркет</strong><br />
  Версия мода: <code>2026.38.4</code><br />
  Варианты: обычный · black (AMOLED) · клон
</p>

<details>
<summary><strong>Что изменено</strong></summary>

- Сняты баннеры морды и flex/Adfox/UrbanAds-экшены
- Скрыт `UrbanAdsView` (рекламный SDK)
- Отключена аналитика (AppMetrica / Adjust / Baobab / Firebase → localhost)
- Экран принудительного обновления закрывается сразу
- Оптимизация графики (xxhdpi), signature killer, завышенный `versionCode`
- **Клон:** `ru.beru.android.clone` рядом со стоком (`com.yandex.passport.clone`)

</details>

<details>
<summary><strong>Загрузки (GitHub Releases)</strong></summary>


| Вариант | arm64-v8a | armeabi-v7a |
|---------|-----------|-------------|
| Обычный | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/market-2026.38.4/market_2026.38.4_mod_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/market-2026.38.4/market_2026.38.4_mod_armeabi-v7a.apk) |
| Клон | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/market-2026.38.4/market_2026.38.4_clone_arm64-v8a.apk) | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/market-2026.38.4/market_2026.38.4_clone_armeabi-v7a.apk) |

Все ассеты тега: [market-2026.38.4](https://github.com/pabushabi/pabushabi_mods/releases/tag/market-2026.38.4)

</details>

---

## Ozon

<p>
  <img src="assets/icons/ozon.png" alt="Ozon" width="72" height="72" align="left" style="margin-right:16px" />
  <strong>Ozon</strong><br />
  Версия мода: <code>19.42.0</code><br />
  Варианты: обычный · black (AMOLED) · клон<br />
  Только <code>arm64-v8a</code>
</p>

<br clear="all" />

<details>
<summary><strong>Что изменено</strong></summary>

- Отключена аналитика (AppsFlyer / Firebase Installations / pagead → localhost)
- Оптимизация графики (xxhdpi)
- Signature killer, завышенный `versionCode`
- **Black:** ночная тема и тёмные поверхности `#000000`
- **Клон:** `ru.ozon.app.android.clone` рядом со стоком, свой account type Ozon ID

</details>

<details>
<summary><strong>Загрузки (GitHub Releases)</strong></summary>


| Вариант | arm64-v8a |
|---------|-----------|
| Обычный | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/ozon-19.42.0/ozon_19.42.0_mod_arm64-v8a.apk) |
| Black | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/ozon-19.42.0/ozon_19.42.0_black_arm64-v8a.apk) |
| Клон | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/ozon-19.42.0/ozon_19.42.0_clone_arm64-v8a.apk) |

Все ассеты тега: [ozon-19.42.0](https://github.com/pabushabi/pabushabi_mods/releases/tag/ozon-19.42.0)

</details>

---

## Дикси

<p>
  <strong>Дикси</strong><br />
  Версия мода: <code>4.16.0</code><br />
  Варианты: обычный · black · клон<br />
  Только <code>arm64-v8a</code>
</p>

<details>
<summary><strong>Что изменено</strong></summary>

- Приложение на Flutter: баннеры, сторис и рекламные виджеты отключены в Dart-снапшоте
- Отключена аналитика (AppMetrica / Gravity Field / Diginetica / Crashlytics / Firebase Installations → localhost)
- Оптимизация графики (xxhdpi)
- Signature killer, завышенный `versionCode`
- **Black:** чёрные сплэш и системное окно, ночной `uiMode`. Цвета самого Flutter-интерфейса не перекрашиваются
- **Клон:** `com.ru.dixy.clone` рядом со стоком

</details>

<details>
<summary><strong>Загрузки (GitHub Releases)</strong></summary>


| Вариант | arm64-v8a |
|---------|-----------|
| Обычный | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/dixy-4.16.0/dixy_4.16.0_mod_arm64-v8a.apk) |
| Black | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/dixy-4.16.0/dixy_4.16.0_black_arm64-v8a.apk) |
| Клон | [скачать](https://github.com/pabushabi/pabushabi_mods/releases/download/dixy-4.16.0/dixy_4.16.0_clone_arm64-v8a.apk) |

Все ассеты тега: [dixy-4.16.0](https://github.com/pabushabi/pabushabi_mods/releases/tag/dixy-4.16.0)

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
