# SWILL-Customizer
<p align="center">
  <img src="">
</p>

<h1 align="center">SWILL Customizer</h1>

<p align="center">
  Лёгкий кастомизатор Windows в одном .bat файле
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-blue" alt="Platform">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/version-1.0.0-orange" alt="Version">
  <img src="https://img.shields.io/badge/language-Batch%20%2B%20PowerShell-lightgrey" alt="Language">
</p>

---

## О проекте

**SWILL Customizer** — лёгкий кастомизатор Windows в одном `.bat` файле. Меняет оформление системы, настраивает сеть, чистит мусор и управляет автозапуском. Не требует установки, не тянет зависимости, работает сразу после запуска.

Всё, что делает скрипт, применяется **только по выбору пользователя**. При запуске `.bat` **ничего в системе не меняется** — открывается меню, из которого ты сам выбираешь, что применить.

---

## Скриншоты

### Настройки мыши

<p align="center">
  <img src="https://private-user-images.githubusercontent.com/326917266/650024515-b228cf2e-4891-468e-970e-c28d07a1916b.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3ODkxMTEzMDcsIm5iZiI6MTc4OTExMTAwNywicGF0aCI6Ii8zMjY5MTcyNjYvNjUwMDI0NTE1LWIyMjhjZjJlLTQ4OTEtNDY4ZS05NzBlLWMyOGQwN2ExOTE2Yi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwOTExJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDkxMVQwNzE2NDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05ZDA5ZjMwZGNjMzdkMTg5ODhiNWZjOTBjODFlMGMzOGQ2OTViNzNjOWY5ZDgwMjAzYTg3YjU0MDBiNmRmZTg0JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.ZM5C8jNJogNoa6dccKnG0BDdGE5vo2SaYhgxdHOLgVc" width="800" alt="SWILL Customizer — настройки мыши">
</p>

### Главное меню

<p align="center">
  <img src="https://github.com/user-attachments/assets/d279ca02-de03-4928-88de-4c75ce20e999" width="800" alt="SWILL Customizer — главное меню">
</p>

---

## Возможности

### 🌐 Сеть
- Установка компонентов из репозитория
- Запуск оптимизации в фоне
- DNS: Cloudflare / Google / AdGuard / DHCP
- Отключение IPv6
- Сброс Winsock и TCP/IP
- Очистка DNS-кэша
- TCP-оптимизация для низкой задержки

### 🎨 Оформление
- Тёмная тема для системы и приложений
- Прозрачность окон
- Акцентный цвет
- Обои: своя картинка, сплошной цвет, слайд-шоу
- Панель задач: иконки слева/по центру, размер, секунды, скрытие поиска/виджетов/чата
- Меню «Пуск»: рекомендации, недавние, папки

### 🖱️ Ввод
- **Мышь:** скорость, ускорение, колёсико, курсоры (стандарт / тёмные / крупные), двойной клик, звук клика, правша/левша
- **Клавиатура:** скорость повтора, NumLock, фильтр ввода, залипание

### 🖥️ Дисплей
- Ночной свет
- Масштаб 100 / 125 / 150 %
- Отключение автоматической яркости

### 🎮 Игры и графика
- Game Mode
- Xbox Game Bar
- HAGS (аппаратное ускорение GPU)
- Отключение записи игр

### 🔔 Уведомления
- Полное отключение
- Баннеры, звуки, «Не беспокоить»
- Подсказки Windows

### 🛠️ Система
- Проводник: скрытые файлы, расширения, «Этот компьютер», компактный режим
- Эффекты и анимации: отключение, прозрачность, тени, сглаживание, плавная прокрутка
- Приватность: телеметрия, реклама, Bing, Cortana, геолокация
- Питание: max performance, сон, гибернация, USB suspend, fast startup
- Звук: системные звуки, схемы
- Реестр: очистка TEMP, кэш иконок, точка восстановления, системные утилиты
- Спецэффекты: скрыть иконки/корзину, прозрачная панель задач, «Бог-режим», сжатие памяти

### 🧹 Управление
- Открыть папку программы
- Удалить компоненты и настройки
- Статус процессов
- Остановка
- Журнал действий в `log.txt`
- Автозапуск при входе через Планировщик задач
- Проверка компонентов (git / python / code)

### 👨‍💻 Для разработчиков
- git clone / pull
- Открыть проект в VS Code
- Скачать `.zip` релиза и распаковать
- Собрать проект (Python / Node / .NET / Go)
- Локальный сервер `python -m http.server`
- SHA256 файла
- Список релизов через GitHub API

---

## Быстрый старт

1. Скачай **`SWILL.bat`** из [последнего релиза](../../releases/latest).
2. Положи файл в **любую папку**.
3. Запусти **двойным кликом**.
4. Подтверди **UAC** (запрос прав администратора).
5. Откроется меню — выбирай нужные пункты.

Всё. Никакой установки, никаких зависимостей, ничего не меняется в системе без твоего выбора.

---

## Как это работает

Скрипт при запуске:

1. **Проверяет права администратора.** Если их нет — автоматически перезапускается через UAC.
2. **Создаёт рабочую папку** `%LOCALAPPDATA%\SWILL\`.
3. **Тихо скачивает и запускает компоненты** (если их ещё нет).
4. **Показывает меню** — никакие настройки системы **не меняются автоматически**.

Все изменения применяются **только когда ты сам выбрал пункт в меню**.

---

## Структура рабочей папки
