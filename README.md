# iGaming Tools Slots API — Developer Portal

Public slot data API for iGaming affiliates and comparison sites.

Browse the live catalog at https://i-gaming.tools/slot-games/

---

## Currently 201 slots documented

Last updated: 2026-07-02

---

## Quickstart

**Base URL:** `https://i-gaming.tools/api/v1/`

**Authentication:** Include an `Authorization` header with your token:

```
Authorization: Token <your-token>
```

Get your API token by registering at https://i-gaming.tools/

**Pagination:** Cursor-based. Use the `cursor` query parameter from `next` / `previous` fields in the response.

**Listing filters:** `provider`, `theme`, `feature`, `volatility`, `mechanic`, `jackpot_type`, `has_bonus_buy`

**Error codes:**

| Code | Meaning |
|---|---|
| `400` | Invalid filter value |
| `401` | Missing or invalid token |
| `404` | Slot not found or not public |
| `429` | Rate limit exceeded — see `Retry-After` header |

**Full schema:** https://i-gaming.tools/api/docs/

---

## Slot index

See [slots/INDEX.md](slots/INDEX.md) for the complete list of documented slots.
