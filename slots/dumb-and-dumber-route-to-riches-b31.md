# Dumb and Dumber Route to Riches

**Provider:** Blueprint Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/dumb-and-dumber-route-to-riches-b31/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/dumb-and-dumber-route-to-riches-b31/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/dumb-and-dumber-route-to-riches-b31/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/dumb-and-dumber-route-to-riches-b31/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/dumb-and-dumber-route-to-riches-b31/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "dumb-and-dumber-route-to-riches-b31",
  "name": "Dumb and Dumber Route to Riches",
  "status": "active",
  "provider": {
    "slug": "blueprint-gaming",
    "name": "Blueprint Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "95.00",
  "rtp_variants": [
    {
      "rtp": "95.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "93.00",
      "variant": "operator_config",
      "is_default": false
    },
    {
      "rtp": "92.00",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "med_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-05-22",
  "themes": [
    {
      "slug": "adventure",
      "name": "Adventure"
    },
    {
      "slug": "road-trip",
      "name": "Road Trip"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
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
      "page_url": "https://i-gaming.tools/slot-games/dumb-and-dumber-route-to-riches-b31/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/dumb-and-dumber-route-to-riches-b31/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/dumb-and-dumber-route-to-riches-b31/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/dumb-and-dumber-route-to-riches-b31/
- **Public page:** https://i-gaming.tools/slot-games/dumb-and-dumber-route-to-riches-b31/
- **Full schema:** https://i-gaming.tools/api/docs/
