# Iumrah Telegram Bot V8.2 — Premium Mini App shell

Cumulative bot-only patch over V8.1.

## Mini App
- New full-screen iumrah splash on every launch.
- First-run 3-step onboarding stored locally in Telegram WebView.
- Premium dashboard inspired by modern wallet-style Mini Apps while retaining iumrah visual language.
- Existing Booking, Status and iumrah Care flows are preserved.
- Added a fourth Help tab with quick routes to connection, status, booking changes and Care.
- New 4-tab glass bottom dock: Booking / Status / Care / Help.
- New trip hero and quick action cards on the Booking home screen.
- Direct query support now also accepts `?tab=help`.

## Telegram bot launch button
- `setChatMenuButton` is now applied both per-user and as the bot-wide default Web App menu button.
- This makes the Mini App available from Telegram's bot menu globally after a user initializes the bot.
- Telegram's separate prominent **Launch app / Open** profile-list entry is controlled by the bot's **Main Mini App** setting in BotFather. If it is not already enabled, set the existing Worker `/mini` URL there once; no website changes are required.

## Files
- `src/index.ts`
- `src/mini-v7.ts`
- `src/support-assets.ts`

## Health
- `1.7.7`
