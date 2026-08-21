# Big Boat Big Catch

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/big-boat-big-catch-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-boat-big-catch-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/big-boat-big-catch-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/big-boat-big-catch-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/big-boat-big-catch-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "big-boat-big-catch-b10",
  "name": "Big Boat Big Catch",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "97.20",
  "rtp_variants": [
    {
      "rtp": "97.20",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.20",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "97.20",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Bonus (Free Spins)",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2025-08-07",
  "themes": [
    {
      "slug": "fishing",
      "name": "Fishing"
    },
    {
      "slug": "ocean",
      "name": "Ocean"
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
      "slug": "money-collect",
      "name": "Money Collect"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/big-boat-big-catch-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/big-boat-big-catch-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-boat-big-catch-b10/demand/
```

**12-month volume (illustrative):** 330 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 50 | flat |
| Switzerland | 30 | flat |
| United Kingdom | 30 | flat |
| Germany | 20 | flat |
| India | 20 | declining |
| Netherlands | 20 | declining |
| South Africa | 20 | declining |
| Argentina | 10 | flat |
| Chile | 10 | flat |
| Estonia | 10 | declining |

> Full per-country breakdown (21 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/big-boat-big-catch-b10/
- **Public page:** https://i-gaming.tools/slot-games/big-boat-big-catch-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
