# Royal Fruits MultiLines

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/royal-fruits-multilines-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/royal-fruits-multilines-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/royal-fruits-multilines-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/royal-fruits-multilines-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/royal-fruits-multilines-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "royal-fruits-multilines-b10",
  "name": "Royal Fruits MultiLines",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "97.15",
  "rtp_variants": [
    {
      "rtp": "97.15",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.16",
      "variant": "default",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-09-11",
  "themes": [
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "royalty",
      "name": "Royalty"
    }
  ],
  "features": [
    {
      "slug": "adjustable-paylines",
      "name": "Adjustable Paylines"
    },
    {
      "slug": "scatter",
      "name": "Scatter"
    },
    {
      "slug": "wild",
      "name": "Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/royal-fruits-multilines-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/royal-fruits-multilines-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/royal-fruits-multilines-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/royal-fruits-multilines-b10/
- **Public page:** https://i-gaming.tools/slot-games/royal-fruits-multilines-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
