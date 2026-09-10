# Mystic Rings

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mystic-rings-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mystic-rings-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mystic-rings-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mystic-rings-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mystic-rings-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mystic-rings-b29",
  "name": "Mystic Rings",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.54",
  "rtp_variants": [
    {
      "rtp": "96.54",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.42",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.71",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "progressive",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Feature (3-5 Scatter)",
      "cost": "39.96",
      "is_default": true
    }
  ],
  "release_date": "2025-06-24",
  "themes": [
    {
      "slug": "fantasy",
      "name": "Fantasy"
    },
    {
      "slug": "fire",
      "name": "Fire"
    },
    {
      "slug": "forest",
      "name": "Forest"
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
      "page_url": "https://i-gaming.tools/slot-games/mystic-rings-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/mystic-rings-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mystic-rings-b29/demand/
```

**12-month volume (illustrative):** 9,040 · **trend:** growing · YoY +11200.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 8,440 | flat |
| Canada | 60 | flat |
| Indonesia | 60 | flat |
| United Kingdom | 60 | growing |
| United States | 60 | declining |
| Panama | 50 | flat |
| Tunisia | 50 | flat |
| Lebanon | 40 | flat |
| Mexico | 30 | growing |
| Germany | 20 | flat |

> Full per-country breakdown (24 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mystic-rings-b29/
- **Public page:** https://i-gaming.tools/slot-games/mystic-rings-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
