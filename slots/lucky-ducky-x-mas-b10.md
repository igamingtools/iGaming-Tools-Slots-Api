# Lucky Ducky X\-mas

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/lucky-ducky-x-mas-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lucky-ducky-x-mas-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/lucky-ducky-x-mas-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/lucky-ducky-x-mas-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/lucky-ducky-x-mas-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "lucky-ducky-x-mas-b10",
  "name": "Lucky Ducky X-mas",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "97.25",
  "rtp_variants": [
    {
      "rtp": "97.25",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.25",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "97.25",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "cluster",
  "reels": 6,
  "rows": 6,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Bonus",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2024-12-17",
  "themes": [
    {
      "slug": "birds",
      "name": "Birds"
    },
    {
      "slug": "christmas",
      "name": "Christmas"
    },
    {
      "slug": "toys",
      "name": "Toys"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
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
      "page_url": "https://i-gaming.tools/slot-games/lucky-ducky-x-mas-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/lucky-ducky-x-mas-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lucky-ducky-x-mas-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/lucky-ducky-x-mas-b10/
- **Public page:** https://i-gaming.tools/slot-games/lucky-ducky-x-mas-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
