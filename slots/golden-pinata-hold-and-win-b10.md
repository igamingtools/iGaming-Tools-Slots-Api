# Golden Pinata Hold and Win

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/golden-pinata-hold-and-win-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/golden-pinata-hold-and-win-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/golden-pinata-hold-and-win-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/golden-pinata-hold-and-win-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/golden-pinata-hold-and-win-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "golden-pinata-hold-and-win-b10",
  "name": "Golden Pinata Hold and Win",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.14",
  "rtp_variants": [
    {
      "rtp": "96.14",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "very_high",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Hold and Win",
      "cost": "40.00",
      "is_default": true
    },
    {
      "label": "Free Hits",
      "cost": "50.00",
      "is_default": false
    }
  ],
  "release_date": "2025-06-03",
  "themes": [
    {
      "slug": "mexican",
      "name": "Mexican"
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
      "page_url": "https://i-gaming.tools/slot-games/golden-pinata-hold-and-win-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/golden-pinata-hold-and-win-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/golden-pinata-hold-and-win-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/golden-pinata-hold-and-win-b10/
- **Public page:** https://i-gaming.tools/slot-games/golden-pinata-hold-and-win-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
