# Poker Kingdom Win

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/poker-kingdom-win-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/poker-kingdom-win-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/poker-kingdom-win-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/poker-kingdom-win-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/poker-kingdom-win-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "poker-kingdom-win-b30",
  "name": "Poker Kingdom Win",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.74",
  "rtp_variants": [
    {
      "rtp": "96.74",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": null,
  "themes": [
    {
      "slug": "cards",
      "name": "Cards"
    },
    {
      "slug": "medieval",
      "name": "Medieval"
    },
    {
      "slug": "royalty",
      "name": "Royalty"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    },
    {
      "slug": "sticky-wins",
      "name": "Sticky Wins"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/poker-kingdom-win-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/poker-kingdom-win-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/poker-kingdom-win-b30/demand/
```

**12-month volume (illustrative):** 4,250 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 1,840 | flat |
| Philippines | 660 | declining |
| Indonesia | 390 | growing |
| India | 260 | growing |
| Thailand | 250 | declining |
| Pakistan | 140 | growing |
| United States | 80 | flat |
| Ukraine | 60 | declining |
| Canada | 40 | flat |
| Malaysia | 40 | growing |

> Full per-country breakdown (37 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/poker-kingdom-win-b30/
- **Public page:** https://i-gaming.tools/slot-games/poker-kingdom-win-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
