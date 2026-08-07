# Keepers Of The Secret

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/keepers-of-the-secret-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/keepers-of-the-secret-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/keepers-of-the-secret-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/keepers-of-the-secret-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/keepers-of-the-secret-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "keepers-of-the-secret-b10",
  "name": "Keepers Of The Secret",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "97.01",
  "rtp_variants": [
    {
      "rtp": "97.01",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy 12 Free Spins",
      "cost": "120.00",
      "is_default": true
    }
  ],
  "release_date": "2024-01-11",
  "themes": [
    {
      "slug": "aztec",
      "name": "Aztec"
    },
    {
      "slug": "jungle",
      "name": "Jungle"
    },
    {
      "slug": "maya",
      "name": "Maya"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "random-wilds",
      "name": "Random Wilds"
    },
    {
      "slug": "scatter",
      "name": "Scatter"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/keepers-of-the-secret-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/keepers-of-the-secret-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/keepers-of-the-secret-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/keepers-of-the-secret-b10/
- **Public page:** https://i-gaming.tools/slot-games/keepers-of-the-secret-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
