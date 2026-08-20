# Blueberry Island

**Provider:** PoggiPlay

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/blueberry-island-b23/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/blueberry-island-b23/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/blueberry-island-b23/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/blueberry-island-b23/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/blueberry-island-b23/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "blueberry-island-b23",
  "name": "Blueberry Island",
  "status": "active",
  "provider": {
    "slug": "poggiplay",
    "name": "PoggiPlay"
  },
  "game_category": "video_slot",
  "rtp_default": "97.11",
  "rtp_variants": [
    {
      "rtp": "97.11",
      "variant": "player_config",
      "is_default": true
    },
    {
      "rtp": "96.99",
      "variant": "player_config",
      "is_default": false
    }
  ],
  "volatility": "med_low",
  "mechanic": "lines",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "unknown",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2021-06-21",
  "themes": [
    {
      "slug": "sweets",
      "name": "Sweets"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "exploding-symbol",
      "name": "Exploding Symbol"
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
      "page_url": "https://i-gaming.tools/slot-games/blueberry-island-b23/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/blueberry-island-b23/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/blueberry-island-b23/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/blueberry-island-b23/
- **Public page:** https://i-gaming.tools/slot-games/blueberry-island-b23/
- **Full schema:** https://i-gaming.tools/api/docs/
