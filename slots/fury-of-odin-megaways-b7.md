# Fury of Odin Megaways

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fury-of-odin-megaways-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fury-of-odin-megaways-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fury-of-odin-megaways-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fury-of-odin-megaways-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fury-of-odin-megaways-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fury-of-odin-megaways-b7",
  "name": "Fury of Odin Megaways",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "95.97",
  "rtp_variants": [
    {
      "rtp": "95.97",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "95.99",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.02",
      "variant": "default",
      "is_default": false
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
  "release_date": "2022-12-01",
  "themes": [
    {
      "slug": "mythology",
      "name": "Mythology"
    },
    {
      "slug": "norse",
      "name": "Norse"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/fury-of-odin-megaways-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fury-of-odin-megaways-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fury-of-odin-megaways-b7/demand/
```

**12-month volume (illustrative):** 1,600 · **trend:** growing · YoY +20.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 120 | flat |
| Canada | 120 | flat |
| United Kingdom | 110 | flat |
| Germany | 80 | flat |
| Indonesia | 80 | flat |
| Malaysia | 80 | flat |
| Thailand | 80 | declining |
| Denmark | 70 | flat |
| Philippines | 70 | growing |
| Greece | 60 | flat |

> Full per-country breakdown (38 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fury-of-odin-megaways-b7/
- **Public page:** https://i-gaming.tools/slot-games/fury-of-odin-megaways-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
