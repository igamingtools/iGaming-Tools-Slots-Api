# Gold Strike

**Provider:** Blueprint Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/gold-strike-b31/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gold-strike-b31/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/gold-strike-b31/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/gold-strike-b31/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/gold-strike-b31/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "gold-strike-b31",
  "name": "Gold Strike",
  "status": "active",
  "provider": {
    "slug": "blueprint-gaming",
    "name": "Blueprint Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "94.00",
  "rtp_variants": [
    {
      "rtp": "94.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "94.00",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.00",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "ways",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Bonus Buy (Wild Strike or Cash Strike)",
      "cost": "75.00",
      "is_default": true
    }
  ],
  "release_date": "2024-01-24",
  "themes": [
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
      "slug": "free-spins-choice",
      "name": "Free Spins Choice"
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
      "page_url": "https://i-gaming.tools/slot-games/gold-strike-b31/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/gold-strike-b31/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gold-strike-b31/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/gold-strike-b31/
- **Public page:** https://i-gaming.tools/slot-games/gold-strike-b31/
- **Full schema:** https://i-gaming.tools/api/docs/
