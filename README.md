# Tamma Lab 🐣

Окремий Telegram Mini App для @Tmgch1_bot: мінітамагочі та прозора локальна діагностика Telegram WebApp API.

## Cloudflare Workers

1. Підключіть цей репозиторій до Cloudflare Workers (Git integration), або виконайте `npm install && npm run deploy` після `npx wrangler login`.
2. Перевірте `https://<worker-url>/health`.
3. У @BotFather задайте кнопку Mini App (`/setmenubutton`) на HTTPS-адресу Worker.
4. Перевірте в Telegram на iPhone та Android.

Бот-токен не потрібен для відкриття Mini App через кнопку меню. Застосунок не отримує приватні чати, сесії чи коди входу та не надсилає діагностику на сервер.
