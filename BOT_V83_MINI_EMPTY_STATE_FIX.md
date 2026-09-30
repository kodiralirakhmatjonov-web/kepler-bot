# Iumrah Telegram Bot V8.3 — Mini App empty-state fix

Cumulative bot-only patch over V8.2.

## Fixed

- Opening the Mini App without a linked booking no longer renders the raw backend error `BOOKING_NOT_LINKED`.
- `/mini/bootstrap` now returns an authenticated empty Mini App shell for users with no linked bookings.
- Added a polished empty booking state with:
  - Connect booking
  - iumrah Care
  - Help
  - persistent bottom navigation
- Splash / onboarding now continue normally even before a booking is linked.
- Added client-side `BOOKING_NOT_LINKED` fallback for safer rolling deployments.
- Hardened booking helpers/header so empty state cannot crash by opening booking detail without a booking.
- Existing Booking / Status / Care / Help functionality is preserved.

## Health

- version: `1.7.8`

## Files

- `src/index.ts`
- `src/mini-v7.ts`
- `src/support-assets.ts`
- `BOT_V83_MINI_EMPTY_STATE_FIX.md`

No website patch is required.
