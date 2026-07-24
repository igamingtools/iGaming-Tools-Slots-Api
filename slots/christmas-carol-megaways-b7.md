# Christmas Carol Megaways

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/christmas-carol-megaways-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/christmas-carol-megaways-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/christmas-carol-megaways-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/christmas-carol-megaways-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/christmas-carol-megaways-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "christmas-carol-megaways-b7",
  "name": "Christmas Carol Megaways",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.58",
  "rtp_variants": [
    {
      "rtp": "96.58",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "megaways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2020-11-01",
  "themes": [
    {
      "slug": "christmas",
      "name": "Christmas"
    },
    {
      "slug": "victorian",
      "name": "Victorian"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/christmas-carol-megaways-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/christmas-carol-megaways-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/christmas-carol-megaways-b7/demand/
```

**12-month volume (illustrative):** 3,950 · **trend:** flat · YoY +1.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 550 | flat |
| Canada | 260 | growing |
| Switzerland | 240 | growing |
| United States | 200 | flat |
| Netherlands | 130 | flat |
| Brazil | 120 | growing |
| India | 120 | flat |
| Germany | 110 | growing |
| Greece | 110 | flat |
| Indonesia | 110 | growing |

> Full per-country breakdown (51 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/christmas-carol-megaways-b7/
- **Public page:** https://i-gaming.tools/slot-games/christmas-carol-megaways-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
