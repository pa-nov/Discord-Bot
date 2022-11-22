# Discord-Bot
Простой дискорд бот

Для работы бота требуется:
* Node.js (16.6.0 или выше)
* Discord.js v14

## Установка

1. Устанавливаем Node.js: https://nodejs.org
2. Запускаем командную строку в папке бота и прописываем: `npm init -y` и `npm install discord.js` (Этим вы установите Discord.js)
3. [Создаём приложение](https://github.com/pa-nov/Discord-Bot/edit/main/README.md#создание-приложения)
4. [Настраиваем бота](https://github.com/pa-nov/Discord-Bot/edit/main/README.md#настройка-бота)
5. Запускаем командную строку в папке бота и прописываем: `node deploy-commands.js` (Этим вы зарегестрируете команды приложения в дискорде)
6. Запускаем командную строку в папке бота и прописываем: `node index.js` (Этим вы запустите бота)

Теперь бот работает, как только вы закроете командную строку из пункта `6` бот перестанет работать

## Создание приложения

1. Переходите на https://discord.com/developers/applications
2. Нажимаете на `New application`
3. Указываете имя бота, соглашаетесь с условиями использования и нажимаете `Create`
4. Копируем `APPLICATION ID`, он понадобится при [настройке бота](https://github.com/pa-nov/Discord-Bot/edit/main/README.md#настройка-бота)
5. В открывшемся окне нажимает на `Bot`, затем на `Add bot`
6. Нажимаем на `Reset Token` и копируем новый токен, он понадобится при [настройке бота](https://github.com/pa-nov/Discord-Bot/edit/main/README.md#настройка-бота)

## Настройка бота

Все настройки хранятся в файлах `settings.json` и `key.json`

В файле `settings.json` необходимо указать:
* `цвет вубхуков`

В файле `key.json` необходимо указать: 
* `токен бота`
* `id бота`
* `id владельца бота`
* `id сервера бота`
* `url вебхука для отправки лс` (необязательно)