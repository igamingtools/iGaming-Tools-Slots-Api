# Red Hot Catch

**Provider:** Blueprint Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/red-hot-catch-b31/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/red-hot-catch-b31/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/red-hot-catch-b31/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/red-hot-catch-b31/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/red-hot-catch-b31/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "red-hot-catch-b31",
  "name": "Red Hot Catch",
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
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "90.00",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "med_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-06-25",
  "themes": [
    {
      "slug": "devils",
      "name": "Devils"
    },
    {
      "slug": "fire",
      "name": "Fire"
    },
    {
      "slug": "fishing",
      "name": "Fishing"
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
      "page_url": "https://i-gaming.tools/slot-games/red-hot-catch-b31/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/red-hot-catch-b31/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/red-hot-catch-b31/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/red-hot-catch-b31/
- **Public page:** https://i-gaming.tools/slot-games/red-hot-catch-b31/
- **Full schema:** https://i-gaming.tools/api/docs/
