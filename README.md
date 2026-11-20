<div align="center">

<a href="#readme">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/readme/hero-ru-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset=".github/readme/hero-ru-light.svg">
    <img alt="Unsub TV: один экран вместо семи подписок" src=".github/readme/hero-ru-dark.svg" width="100%">
  </picture>
</a>

**Русский** · [English](README.en.md)

<a href="https://github.com/Startupingarage/unsub-tv-releases/releases"><img alt="Последняя версия" src="https://img.shields.io/github/v/release/Startupingarage/unsub-tv-releases?include_prereleases&style=for-the-badge&label=%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%8F&color=3ddc97&labelColor=0d1311"></a>
<a href="https://github.com/Startupingarage/unsub-tv-releases/releases"><img alt="Скачивания" src="https://img.shields.io/github/downloads/Startupingarage/unsub-tv-releases/total?style=for-the-badge&label=%D1%81%D0%BA%D0%B0%D1%87%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F&color=1fb5c9&labelColor=0d1311"></a>
<img alt="Android TV 8.0+" src="https://img.shields.io/badge/Android%20TV-8.0%2B-7b5cff?style=for-the-badge&labelColor=0d1311">
<img alt="Цена: бесплатно" src="https://img.shields.io/badge/%D1%86%D0%B5%D0%BD%D0%B0-0%20%E2%82%BD%20%D0%BD%D0%B0%D0%B2%D1%81%D0%B5%D0%B3%D0%B4%D0%B0-3ddc97?style=for-the-badge&labelColor=0d1311">

<br><br>

<a href="https://github.com/Startupingarage/unsub-tv-releases/releases"><img alt="Скачать для телефона Android" src=".github/readme/btn-android-ru.svg" height="56"></a>&nbsp;
<a href="https://github.com/Startupingarage/unsub-tv-releases/releases"><img alt="Скачать для ПК с Windows" src=".github/readme/btn-windows-ru.svg" height="56"></a>&nbsp;
<a href="https://github.com/Startupingarage/unsub-tv-releases/releases"><img alt="Скачать TV APK" src=".github/readme/btn-tv-ru.svg" height="56"></a>

<sub>Открытая бета · телефон или ПК и телевизор должны быть в одной домашней сети</sub>

<br>

[**🚀 Быстрый старт (установка)**](#быстрый-старт) &nbsp;·&nbsp; [**Зачем**](#зачем) &nbsp;·&nbsp; [**Возможности**](#возможности) &nbsp;·&nbsp; [**Пульт**](#пульт) &nbsp;·&nbsp; [**Как устроено**](#как-устроено) &nbsp;·&nbsp; [**Вопросы**](#вопросы) &nbsp;·&nbsp; [**Приватность**](#приватность)

<br>

<img alt="Unsub TV на телевизоре: главная, фильм в фокусе, действия с фильмом, мои списки, результаты голосового поиска, нижние ряды" src=".github/readme/tour-ru.svg" width="100%">

</div>

<img src=".github/readme/divider.svg" width="100%" alt="">

## Быстрый старт

> [!IMPORTANT]
> **Все файлы лежат на странице [Releases →](https://github.com/Startupingarage/unsub-tv-releases/releases)**. Бери самый верхний выпуск и в блоке **Assets** скачай файл под своё устройство.

### Что скачать

| Устройство | Файл в Releases | Что это |
| :-- | :-- | :-- |
| 📱 **Телефон Android** | `UnsubTV-Companion-<версия>.apk` | **APK-приложение для телефона.** Ставит Unsub TV на телевизор, обновляет его и работает как пульт. **Основной способ.** |
| 💻 **Компьютер с Windows** | `UnsubTV-Setup-<версия>.zip` | **Мастер установки для Windows.** Делает то же самое, но с ПК. |
| 📺 **Сам телевизор** | `UnsubTV-<версия>.apk` | Голое приложение для ТВ. Нужно только для ручного обновления. |
| 🔐 | `SHA256SUMS.txt` | Контрольные суммы, если хочешь сверить файлы. |

> [!TIP]
> Companion и Setup уже содержат свежий TV APK внутри. Отдельно его качать не нужно.

### Шаг 1. Одна сеть

Подключи телефон или ПК и телевизор **к одному домашнему роутеру**. Гостевая сеть и «изоляция устройств» в роутере мешают подключению. VPN на телефоне или ПК тоже иногда блокирует локальную сеть, тогда на время установки его лучше выключить.

### Шаг 2. Поставь установщик

<details open>
<summary><b>📱 С телефона Android</b> &nbsp;<sub>основной способ</sub></summary>
<br>

1. Скачай `UnsubTV-Companion-<версия>.apk` из [Releases](https://github.com/Startupingarage/unsub-tv-releases/releases) прямо на телефон.
2. Открой файл. Если Android спросит разрешение на установку, разреши его только тому приложению, через которое открыл APK (браузер или «Файлы»).
3. Запусти **Unsub TV Companion** и выбери **«Установить на новый ТВ»**.

</details>

<details>
<summary><b>💻 С компьютера Windows</b></summary>
<br>

1. Скачай `UnsubTV-Setup-<версия>.zip` из [Releases](https://github.com/Startupingarage/unsub-tv-releases/releases).
2. Распакуй архив **полностью**: из ZIP напрямую мастер не запустится.
3. Запусти `UnsubTV-Setup.exe` и выбери **«Новая установка»**. Если Windows предупредит о неизвестном издателе, сначала сверь контрольную сумму из `SHA256SUMS.txt`.

</details>

### Шаг 3. Подключи телевизор

Мастер сам покажет, где на ТВ включить **отладку по Wi-Fi**. Дальше пара моментов, на которых обычно спотыкаются:

- **Адрес подключения** показан на основном экране отладки по Wi-Fi.
- **Адрес сопряжения и шестизначный код** показаны в отдельном окне «Подключить устройство с помощью кода подключения». Открывай его, когда мастер попросит, и держи открытым до подтверждения.
- Прими запрос на телевизоре.

### Шаг 4. Готово

Дождись итогового экрана мастера: сообщение «готовлю файл» ещё не значит, что всё установлено. Необязательные шаги можно пропустить и пройти позже при обновлении. Потом нажми <kbd>Home</kbd> на пульте, и ты в Unsub TV. 🍿

<details>
<summary><b>🔄 Как обновиться</b></summary>
<br>

Скачай свежий Companion или Setup из [Releases](https://github.com/Startupingarage/unsub-tv-releases/releases) и выбери **«Обновить Unsub TV»**. Новая версия ставится поверх старой, настройки и списки сохраняются.

</details>

<details>
<summary><b>🧯 Не подключается?</b></summary>
<br>

- Проверь, что оба устройства в одной сети и это не гостевой Wi-Fi.
- Выключи VPN на телефоне или ПК и на ТВ на время подключения.
- После перезагрузки ТВ порт отладки может смениться. Обнови поиск в мастере или введи текущий адрес с экрана отладки.
- Если устройства уже сопряжены, код вводить заново не нужно: хватит адреса подключения.

</details>

**Требования:** Android TV или Google TV с Android 8.0+ (API 26). Для Companion тоже нужен Android 8.0+.

<img src=".github/readme/divider.svg" width="100%" alt="">

## Зачем

Платишь за пять–семь сервисов, а вечером скачешь между пятью–семью приложениями в поисках одного фильма. А после работы хочется просто сесть и нажать «плей».

**Unsub TV — один главный экран для всего этого.** Рекомендации YouTube, фильмы, твои приложения и твои списки на одном экране, и всё это управляется обычным пультом. Без аккаунта Unsub, без рекламы, без подписки. Бесплатно и навсегда: проект живёт только на донатах.

<img src=".github/readme/divider.svg" width="100%" alt="">

## Возможности

<table>
  <tr>
    <td width="33%" valign="top">
      <img src=".github/readme/shots/ru/home.jpg" alt="Главный экран">
      <h3>🏠 Один главный экран</h3>
      Рекомендации YouTube и фильмы рядом с любимыми приложениями. Фокус светится — видно с дивана.
    </td>
    <td width="33%" valign="top">
      <img src=".github/readme/shots/ru/voice-results.jpg" alt="Результаты голосового поиска">
      <h3>🎙️ Просто скажи</h3>
      Жми микрофон на пульте и назови фильм или опиши настроение: <i>«старая фантастика»</i>, <i>«комедия на вечер»</i>.
    </td>
    <td width="33%" valign="top">
      <img src=".github/readme/shots/ru/lists.jpg" alt="Мои списки">
      <h3>🔖 Мои списки</h3>
      «На потом», «Продолжить», «Просмотрено» и «Не предлагать». Всё хранится на телевизоре.
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <img src=".github/readme/shots/ru/movie.jpg" alt="Действия с фильмом">
      <h3>⚡ Всё в один клик</h3>
      Смотреть, отложить, отметить просмотренным, скрыть, найти похожее. Удерживай <kbd>OK</kbd> на любой карточке.
    </td>
    <td width="33%" valign="top">
      <img src=".github/readme/shots/ru/companion.jpg" alt="Android Companion">
      <h3>📱 Телефон вместо пульта</h3>
      Companion ставит и обновляет приложение на ТВ, набирает запросы за тебя и открывает списки.
    </td>
    <td width="33%" valign="top">
      <img src=".github/readme/shots/ru/settings.jpg" alt="Настройки">
      <h3>🛠️ Настрой под себя</h3>
      Главный экран, поиск, экран и звук, пульт и таймер сна. Русский и английский из коробки.
    </td>
  </tr>
</table>

<details>
<summary><b>Что ещё умеет</b></summary>
<br>

- **Подбор по описанию.** Добавь свой ключ Groq и попроси «космическую фантастику 70-х». Поиск по названию работает и без ключа.
- **Набор с телефона.** Отсканируй QR на телевизоре и отправь текст с телефона вместо набора стрелками.
- **Обновления не ломают твоё.** Новая версия ставится поверх старой; настройки, списки и ключи остаются.
- **Лёгкий путь назад.** Один переключатель в настройках возвращает родной главный экран телевизора.
- **Бережёт старые приставки.** Статичный фон, ограниченные загрузки и без увеличения фокуса при малом объёме памяти.
- **Работает сам.** После настройки телевизору не нужны ни телефон, ни постоянно включённый ПК.

</details>

<img src=".github/readme/divider.svg" width="100%" alt="">

## Пульт

| Кнопка | Что происходит |
| :-- | :-- |
| <kbd>🎤</kbd> | Голосовой поиск откуда угодно |
| <kbd>OK</kbd> | Открыть карточку |
| <kbd>OK</kbd> *удерживать* | Ещё действия: на потом, просмотрено, скрыть, похожее |
| <kbd>▼</kbd> | Вниз — «Продолжить просмотр» и «На потом» |
| <kbd>Home</kbd> | Назад в Unsub TV |

<img src=".github/readme/divider.svg" width="100%" alt="">

## Как устроено

```mermaid
flowchart LR
    phone["📱 Companion<br/>телефон Android"] -- "установка · обновление · пульт" --> tv
    pc["💻 Windows Setup"] -- "установка · обновление" --> tv
    tv(["📺 Unsub TV<br/>твой главный экран"])
    yt["▶️ YouTube"] -- "твои рекомендации" --> tv
    films["🎬 Каталог фильмов"] -- "поиск · постеры" --> tv
    rel[("GitHub Releases")] -. "новые версии" .-> phone
    rel -. "новые версии" .-> pc
```

<img src=".github/readme/divider.svg" width="100%" alt="">

## Вопросы

<details>
<summary><b>Это правда бесплатно?</b></summary>
<br>
Да. Ни подписки, ни рекламы, ни платной версии. Проект живёт только на донатах.
</details>

<details>
<summary><b>Я не потеряю родной экран телевизора?</b></summary>
<br>
Нет. <b>Настройки → Главный экран → Главный экран → Заводской</b> возвращает его. Чтобы вернуться обратно, открой Unsub TV из списка приложений и переключи назад. Приложения и аккаунты остаются на месте.
</details>

<details>
<summary><b>Телефон или ПК должны быть всё время включены?</b></summary>
<br>
Нет. Они нужны для установки и обновлений. Дальше телевизор работает сам.
</details>

<details>
<summary><b>Нужен ли ключ Groq?</b></summary>
<br>
Нет. Поиск по названию и голосом работает без него. Ключ нужен только для подбора по описанию, и его можно добавить позже при обновлении.
</details>

<details>
<summary><b>Какие устройства поддерживаются?</b></summary>
<br>
Приставки и телевизоры на Android TV и Google TV с Android 8.0 или новее. Основное тестовое устройство — Xiaomi TV Box S (3-го поколения) с Android 14.
</details>

<img src=".github/readme/divider.svg" width="100%" alt="">

## Планы

- [x] Русский и английский в приложении для ТВ, Android Companion и Windows Setup
- [x] Установка и обновление с телефона или ПК
- [x] Голосовой поиск и подбор по описанию
- [x] Мои списки: на потом, продолжить, просмотрено, не предлагать
- [x] Новый главный экран с большой карточкой (beta 6)
- [ ] Стабильная 1.2.0

<img src=".github/readme/divider.svg" width="100%" alt="">

## Приватность

Unsub TV хранит настройки, списки, недавно открытые материалы и кеш рекомендаций на телевизоре. Если добавить ключ Groq, приложение зашифрует его через Android Keystore и будет отправлять текст запроса в Groq только при подборе по описанию. Голосовой ввод работает через системное распознавание речи телевизора.

## Поддержать

Unsub TV бесплатный и таким останется. Если он сэкономил тебе пару подписок — поставь ⭐ репозиторию и расскажи другу.

## Лицензия и благодарности

Unsub TV распространяется по закрытой лицензии. Все права защищены. Сторонние компоненты сохраняют свои лицензии.

На скриншотах демонстрационные данные. Природные и космические кадры с Wikimedia Commons: Kevin M. Gill, Jakub Hałun (CC BY 4.0); Michal Klajban, Giles Laurent, Gerda Arendt (CC BY-SA 4.0); Sonse (CC BY 2.0); NASA (общественное достояние). Постеры фильмов в витрине — общественное достояние.

<div align="center">
<br>
<img src=".github/readme/divider.svg" width="60%" alt="">
<br>
<sub>Сделано для вечеров на диване · <a href="#readme">наверх ↑</a></sub>
</div>
