# FaceWorld starter app

A mobile-first social-network demo that can be opened in a browser. It includes:
- Feed with sample posts
- Create text/photo posts
- Likes and comments
- Profile editing
- Friend suggestions and request demo
- Notifications
- Search across visible posts
- Responsive mobile layout

## Run it
Open `index.html` in a browser, or upload the file to a static hosting service.

## Important limitations
This is a frontend prototype. Data is stored in the browser's localStorage, so it is not shared across users/devices and can be cleared by the browser. It does not yet have a real server, shared database, verified Telegram authentication, secure messaging, or production moderation. Do not use it to collect sensitive information.

## Next steps for Telegram
1. Create a bot using https://t.me/BotFather
2. Host the app at an HTTPS URL.
3. Add Telegram Mini App SDK integration and configure the web app URL with BotFather.
4. Build a backend that validates Telegram `initData` server-side and stores users/posts in a shared database.
5. Add authorization, rate limiting, upload validation, reporting/blocking, and tests before public launch.
