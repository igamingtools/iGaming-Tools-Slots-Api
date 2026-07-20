# Lobster Bob's Sea Food and Win It

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/lobster-bob-s-sea-food-and-win-it-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lobster-bob-s-sea-food-and-win-it-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/lobster-bob-s-sea-food-and-win-it-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/lobster-bob-s-sea-food-and-win-it-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/lobster-bob-s-sea-food-and-win-it-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "lobster-bob-s-sea-food-and-win-it-b7",
  "name": "Lobster Bob's Sea Food and Win It",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.04",
  "rtp_variants": [
    {
      "rtp": "96.04",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.02",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.02",
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
      "cost": "50.00",
      "is_default": true
    },
    {
      "label": "Buy Hold & Spinner",
      "cost": "50.00",
      "is_default": false
    }
  ],
  "release_date": "2024-04-01",
  "themes": [
    {
      "slug": "fishing",
      "name": "Fishing"
    },
    {
      "slug": "food",
      "name": "Food"
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
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/lobster-bob-s-sea-food-and-win-it-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  }
}
```

## Search Demand

`GET /api/v1/slots/lobster-bob-s-sea-food-and-win-it-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lobster-bob-s-sea-food-and-win-it-b7/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/lobster-bob-s-sea-food-and-win-it-b7/
- **Public page:** https://i-gaming.tools/slot-games/lobster-bob-s-sea-food-and-win-it-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
