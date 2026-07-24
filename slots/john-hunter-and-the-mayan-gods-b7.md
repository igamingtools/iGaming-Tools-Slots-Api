# John Hunter and the Mayan Gods

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/john-hunter-and-the-mayan-gods-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/john-hunter-and-the-mayan-gods-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/john-hunter-and-the-mayan-gods-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/john-hunter-and-the-mayan-gods-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/john-hunter-and-the-mayan-gods-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "john-hunter-and-the-mayan-gods-b7",
  "name": "John Hunter and the Mayan Gods",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.46",
  "rtp_variants": [
    {
      "rtp": "96.46",
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
  "release_date": "2020-12-10",
  "themes": [
    {
      "slug": "adventure",
      "name": "Adventure"
    },
    {
      "slug": "maya",
      "name": "Maya"
    }
  ],
  "features": [
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
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
      "page_url": "https://i-gaming.tools/slot-games/john-hunter-and-the-mayan-gods-b7/"
    }
  },
  "series": {
    "slug": "john-hunter",
    "name": "John Hunter"
  }
}
```

## Search Demand

`GET /api/v1/slots/john-hunter-and-the-mayan-gods-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/john-hunter-and-the-mayan-gods-b7/demand/
```

**12-month volume (illustrative):** 340 · **trend:** declining · YoY -37.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 60 | declining |
| Netherlands | 30 | flat |
| Sweden | 30 | flat |
| United Kingdom | 30 | declining |
| Germany | 20 | flat |
| Greece | 20 | declining |
| New Zealand | 20 | flat |
| Philippines | 20 | flat |
| Romania | 20 | flat |
| Austria | 10 | flat |

> Full per-country breakdown (18 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/john-hunter-and-the-mayan-gods-b7/
- **Public page:** https://i-gaming.tools/slot-games/john-hunter-and-the-mayan-gods-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
