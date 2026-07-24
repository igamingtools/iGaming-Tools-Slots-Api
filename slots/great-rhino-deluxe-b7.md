# Great Rhino Deluxe

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/great-rhino-deluxe-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/great-rhino-deluxe-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/great-rhino-deluxe-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/great-rhino-deluxe-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/great-rhino-deluxe-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "great-rhino-deluxe-b7",
  "name": "Great Rhino Deluxe",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.54",
  "rtp_variants": [
    {
      "rtp": "96.54",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2020-07-30",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
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
      "page_url": "https://i-gaming.tools/slot-games/great-rhino-deluxe-b7/"
    }
  },
  "series": {
    "slug": "great-rhino",
    "name": "Great Rhino"
  }
}
```

## Search Demand

`GET /api/v1/slots/great-rhino-deluxe-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/great-rhino-deluxe-b7/demand/
```

**12-month volume (illustrative):** 1,530 · **trend:** declining · YoY -23.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 240 | flat |
| Canada | 140 | declining |
| Brazil | 120 | flat |
| Indonesia | 120 | growing |
| Germany | 90 | growing |
| Mexico | 90 | flat |
| Argentina | 70 | flat |
| Malaysia | 60 | flat |
| Denmark | 50 | flat |
| Netherlands | 50 | growing |

> Full per-country breakdown (36 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/great-rhino-deluxe-b7/
- **Public page:** https://i-gaming.tools/slot-games/great-rhino-deluxe-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
