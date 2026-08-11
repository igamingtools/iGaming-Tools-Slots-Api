# Domnitor's Treasure

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/domnitor-s-treasure-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/domnitor-s-treasure-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/domnitor-s-treasure-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/domnitor-s-treasure-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/domnitor-s-treasure-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "domnitor-s-treasure-b10",
  "name": "Domnitor's Treasure",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "95.24",
  "rtp_variants": [
    {
      "rtp": "95.24",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "94.95",
      "variant": "feature",
      "is_default": false
    },
    {
      "rtp": "95.58",
      "variant": "feature",
      "is_default": false
    }
  ],
  "volatility": "med_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "52.00",
      "is_default": true
    },
    {
      "label": "Hold and Win",
      "cost": "39.60",
      "is_default": false
    }
  ],
  "release_date": "2023-01-12",
  "themes": [
    {
      "slug": "medieval",
      "name": "Medieval"
    },
    {
      "slug": "royalty",
      "name": "Royalty"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "giant-symbol",
      "name": "Giant Symbol"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/domnitor-s-treasure-b10/"
    }
  },
  "series": {
    "slug": "domnitors",
    "name": "Domnitors"
  }
}
```

## Search Demand

`GET /api/v1/slots/domnitor-s-treasure-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/domnitor-s-treasure-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/domnitor-s-treasure-b10/
- **Public page:** https://i-gaming.tools/slot-games/domnitor-s-treasure-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
