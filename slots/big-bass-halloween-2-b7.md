# Big Bass Halloween 2

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/big-bass-halloween-2-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-bass-halloween-2-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/big-bass-halloween-2-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/big-bass-halloween-2-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/big-bass-halloween-2-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "big-bass-halloween-2-b7",
  "name": "Big Bass Halloween 2",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.71",
  "rtp_variants": [
    {
      "rtp": "96.71",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.71",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2024-10-21",
  "themes": [
    {
      "slug": "fishing",
      "name": "Fishing"
    },
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "zombies",
      "name": "Zombies"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/big-bass-halloween-2-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  },
  "series": {
    "slug": "big-bass",
    "name": "Big Bass"
  }
}
```

## Search Demand

`GET /api/v1/slots/big-bass-halloween-2-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-bass-halloween-2-b7/demand/
```

**12-month volume (illustrative):** 13,550 · **trend:** flat · YoY -3.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 2,420 | flat |
| Greece | 1,540 | declining |
| Brazil | 1,500 | flat |
| Germany | 830 | growing |
| Spain | 610 | declining |
| Netherlands | 570 | flat |
| Canada | 440 | growing |
| Switzerland | 390 | flat |
| Italy | 320 | flat |
| Romania | 320 | flat |

> Full per-country breakdown (53 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/big-bass-halloween-2-b7/
- **Public page:** https://i-gaming.tools/slot-games/big-bass-halloween-2-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
