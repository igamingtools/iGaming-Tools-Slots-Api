# Elite Coin 2

**Provider:** PoggiPlay

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/elite-coin-2-b23/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/elite-coin-2-b23/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/elite-coin-2-b23/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/elite-coin-2-b23/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/elite-coin-2-b23/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "elite-coin-2-b23",
  "name": "Elite Coin 2",
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
  "rows": 5,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2026-11-10",
  "themes": [
    {
      "slug": "casino",
      "name": "Casino"
    },
    {
      "slug": "classic",
      "name": "Classic"
    },
    {
      "slug": "fruits",
      "name": "Fruits"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
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
      "page_url": "https://i-gaming.tools/slot-games/elite-coin-2-b23/"
    }
  },
  "series": {
    "slug": "elite-coin",
    "name": "Elite Coin"
  }
}
```

## Search Demand

`GET /api/v1/slots/elite-coin-2-b23/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/elite-coin-2-b23/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/elite-coin-2-b23/
- **Public page:** https://i-gaming.tools/slot-games/elite-coin-2-b23/
- **Full schema:** https://i-gaming.tools/api/docs/
