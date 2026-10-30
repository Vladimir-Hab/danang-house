# Da Nang House

Каталог аренды жилья в Дананге с ботом, Mini App, подпиской на новые объявления и автопостингом в группу. / A catalog of rental housing in Da Nang with a bot, a Mini App, subscriptions to new listings and auto-posting to a group.

**Сайт / Site:** https://dananghouse.ru/ · **Бот / Bot:** https://t.me/DanangHomebot · **Mini App:** https://t.me/DanangHomebot/app · **Группа / Group:** https://t.me/danang_house_chat

> В этом репозитории только описание проекта. Исходный код закрыт. / This repository contains the project description only; the source code is private.

## Что внутри / What it is

- **Каталог:** 3000+ объявлений, фильтры по району, типу жилья и бюджету в донгах, сортировка, избранное, фото и видео в карточке, карта и кнопка связи. База обновляется автоматически каждые 15 секунд.
- **Автоматизация:** объявление с сайта через webhook попадает в n8n, сохраняется в PostgreSQL, публикуется в чат и обновляет каталог.
- **Mini App и подписки:** каталог внутри Telegram, карточка с галереей и картой, сохранённые поиски и подписка на новые объявления по критериям.
- **Группа:** топики по бюджету, автопостинг объявлений и закреплённая кнопка «Открыть каталог».

Схема: форма на сайте → webhook n8n → PostgreSQL → чат и каталог → бот.

## Стек / Stack

n8n · PostgreSQL · Telegram Bot API · Telegram Mini App · webhooks

## Автор / Author

Владимир Кальянов / Vladimir Kalianov — https://oneswitch.ru · [описание проекта](https://oneswitch.ru/raboty/danang-house/)
