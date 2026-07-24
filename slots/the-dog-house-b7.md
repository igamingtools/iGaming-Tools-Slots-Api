# The Dog House

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/the-dog-house-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/the-dog-house-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/the-dog-house-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/the-dog-house-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/the-dog-house-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "the-dog-house-b7",
  "name": "The Dog House",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.51",
  "rtp_variants": [
    {
      "rtp": "96.51",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2019-05-09",
  "themes": [
    {
      "slug": "dogs",
      "name": "Dogs"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
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
      "page_url": "https://i-gaming.tools/slot-games/the-dog-house-b7/"
    }
  },
  "series": {
    "slug": "the-dog-house",
    "name": "The Dog House"
  }
}
```

## Search Demand

`GET /api/v1/slots/the-dog-house-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/the-dog-house-b7/demand/
```

**12-month volume (illustrative):** 28,530 · **trend:** declining · YoY -16.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 5,800 | growing |
| Ukraine | 2,610 | flat |
| Germany | 2,130 | declining |
| Brazil | 1,830 | flat |
| Belarus | 1,400 | growing |
| Romania | 1,140 | flat |
| Indonesia | 800 | declining |
| United Kingdom | 800 | flat |
| Netherlands | 750 | growing |
| Latvia | 670 | declining |

> Full per-country breakdown (61 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/the-dog-house-b7/
- **Public page:** https://i-gaming.tools/slot-games/the-dog-house-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
