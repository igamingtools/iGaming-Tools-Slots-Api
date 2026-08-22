# Bonanza Billion Xtreme

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/bonanza-billion-xtreme-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/bonanza-billion-xtreme-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/bonanza-billion-xtreme-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/bonanza-billion-xtreme-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/bonanza-billion-xtreme-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "bonanza-billion-xtreme-b10",
  "name": "Bonanza Billion Xtreme",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
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
      "rtp": "96.00",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.03",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "scatter_pays",
  "reels": 6,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins",
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2026-03-10",
  "themes": [
    {
      "slug": "classic",
      "name": "Classic"
    },
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "gems",
      "name": "Gems"
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
      "slug": "multiplier-spots",
      "name": "Multiplier Spots"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/bonanza-billion-xtreme-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/bonanza-billion-xtreme-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/bonanza-billion-xtreme-b10/demand/
```

**12-month volume (illustrative):** 860 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 60 | declining |
| Greece | 50 | flat |
| Australia | 40 | flat |
| Austria | 40 | growing |
| Germany | 40 | declining |
| Netherlands | 40 | flat |
| New Zealand | 40 | flat |
| United Kingdom | 40 | declining |
| United States | 40 | declining |
| Hungary | 30 | growing |

> Full per-country breakdown (37 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/bonanza-billion-xtreme-b10/
- **Public page:** https://i-gaming.tools/slot-games/bonanza-billion-xtreme-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
