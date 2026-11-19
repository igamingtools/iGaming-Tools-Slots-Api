# Fortune Rico

**Provider:** PoggiPlay

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fortune-rico-b23/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fortune-rico-b23/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fortune-rico-b23/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fortune-rico-b23/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fortune-rico-b23/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fortune-rico-b23",
  "name": "Fortune Rico",
  "status": "active",
  "provider": {
    "slug": "poggiplay",
    "name": "PoggiPlay"
  },
  "game_category": "video_slot",
  "rtp_default": "96.67",
  "rtp_variants": [
    {
      "rtp": "96.67",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Jaguar Feature",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2026-10-15",
  "themes": [
    {
      "slug": "adventure",
      "name": "Adventure"
    },
    {
      "slug": "jaguars",
      "name": "Jaguars"
    },
    {
      "slug": "jungle",
      "name": "Jungle"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
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
      "page_url": "https://i-gaming.tools/slot-games/fortune-rico-b23/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fortune-rico-b23/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fortune-rico-b23/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fortune-rico-b23/
- **Public page:** https://i-gaming.tools/slot-games/fortune-rico-b23/
- **Full schema:** https://i-gaming.tools/api/docs/
