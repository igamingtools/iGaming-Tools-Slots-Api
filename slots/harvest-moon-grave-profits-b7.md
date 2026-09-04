# Harvest Moon – Grave Profits

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/harvest-moon-grave-profits-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/harvest-moon-grave-profits-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/harvest-moon-grave-profits-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/harvest-moon-grave-profits-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/harvest-moon-grave-profits-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "harvest-moon-grave-profits-b7",
  "name": "Harvest Moon – Grave Profits",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.52",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.46",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Respins",
      "cost": "120.00",
      "is_default": true
    },
    {
      "label": "Super Respins",
      "cost": "400.00",
      "is_default": false
    }
  ],
  "release_date": "2026-08-13",
  "themes": [
    {
      "slug": "aliens",
      "name": "Aliens"
    },
    {
      "slug": "cyberpunk",
      "name": "Cyberpunk"
    },
    {
      "slug": "horror",
      "name": "Horror"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    },
    {
      "slug": "random-wilds",
      "name": "Random Wilds"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/harvest-moon-grave-profits-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/harvest-moon-grave-profits-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/harvest-moon-grave-profits-b7/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/harvest-moon-grave-profits-b7/
- **Public page:** https://i-gaming.tools/slot-games/harvest-moon-grave-profits-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
