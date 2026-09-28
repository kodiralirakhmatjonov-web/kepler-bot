# Iumrah Telegram Bot V8.1 — Care photo + booking-not-linked photo

Cumulative bot-only patch over V8.0.

## Included
- `iumrah Care` now sends a photo card instead of a dry text-only message.
- Connected the provided `iumrah Support` artwork as the care message asset.
- `Бронь ещё не подключена` / `No booking is linked yet` now also sends a photo message instead of a plain text block.
- Added `booking_not_linked` support asset and wired it into both:
  - empty linked-bookings state
  - detached / not-linked fallback state
- Version bumped to `1.7.6`.

## Files
- `src/index.ts`
- `src/support-assets.ts`
- `BOT_V81_CARE_AND_NOT_LINKED_PHOTO.md`
