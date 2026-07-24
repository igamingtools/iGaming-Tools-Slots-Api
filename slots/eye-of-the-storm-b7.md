# Eye of the Storm

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/eye-of-the-storm-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/eye-of-the-storm-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/eye-of-the-storm-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/eye-of-the-storm-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/eye-of-the-storm-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "eye-of-the-storm-b7",
  "name": "Eye of the Storm",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.71",
  "rtp_variants": [
    {
      "rtp": "96.71",
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
  "release_date": "2021-02-08",
  "themes": [
    {
      "slug": "egyptian",
      "name": "Egyptian"
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
      "page_url": "https://i-gaming.tools/slot-games/eye-of-the-storm-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  }
}
```

## Search Demand

`GET /api/v1/slots/eye-of-the-storm-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/eye-of-the-storm-b7/demand/
```

**12-month volume (illustrative):** 1,290 · **trend:** growing · YoY +19.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Netherlands | 140 | flat |
| Brazil | 120 | flat |
| Switzerland | 120 | flat |
| United Kingdom | 110 | flat |
| United States | 80 | growing |
| Germany | 70 | flat |
| Portugal | 70 | flat |
| Argentina | 60 | flat |
| Canada | 60 | flat |
| Cyprus | 40 | flat |

> Full per-country breakdown (33 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/eye-of-the-storm-b7/
- **Public page:** https://i-gaming.tools/slot-games/eye-of-the-storm-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
