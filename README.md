# Site Kit для OAuth Verification

Этот набор файлов нужен для трех публичных страниц, которые Google обычно
просит при OAuth verification:

- главная страница приложения;
- privacy policy;
- terms of service.

## Что внутри

- `index.html` - главная страница
- `privacy-policy.html` - политика конфиденциальности
- `terms-of-service.html` - условия использования

## Важный нюанс про Google Sites

`Google Sites` обычно не публикует загруженный `HTML` как "готовую страницу
сайта" через простой upload файла.

Поэтому используйте этот набор так:

1. Откройте `Google Sites`.
2. Создайте сайт.
3. Создайте на нем 3 страницы:
   - `Home`
   - `Privacy Policy`
   - `Terms of Service`
4. Откройте соответствующий `HTML`-файл в браузере.
5. Скопируйте текст и структуру со страницы.
6. Вставьте это содержимое в нужную страницу в `Google Sites`.
7. Опубликуйте сайт.

## Какие ссылки потом вставлять в Google Cloud

После публикации у вас будут ссылки примерно такого вида:

- `https://sites.google.com/view/NAIMTECH-PORTAL`
- `https://sites.google.com/view/NAIMTECH-PORTAL/privacy-policy`
- `https://sites.google.com/view/NAIMTECH-PORTAL/terms-of-service`

Именно их потом вставляйте в:

- `Application home page`
- `Application privacy policy link`
- `Application terms of service link`

## Какой email сейчас указан

Во всех страницах указан контакт:

- `skeepowski@gmail.com`

Если захотите, я потом могу так же подготовить для вас вторую версию:

- более официальную;
- более короткую;
- полностью на английском;
- полностью на русском.
