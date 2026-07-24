# Jurassic Giants

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/jurassic-giants-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/jurassic-giants-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/jurassic-giants-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/jurassic-giants-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/jurassic-giants-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "jurassic-giants-b7",
  "name": "Jurassic Giants",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.01",
  "rtp_variants": [
    {
      "rtp": "96.01",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2017-06-28",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "dinosaurs",
      "name": "Dinosaurs"
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
      "page_url": "https://i-gaming.tools/slot-games/jurassic-giants-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/jurassic-giants-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/jurassic-giants-b7/demand/
```

**12-month volume (illustrative):** 220 · **trend:** flat · YoY -4.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Argentina | 20 | growing |
| Brazil | 20 | flat |
| Finland | 20 | flat |
| Germany | 20 | flat |
| Portugal | 20 | flat |
| United States | 20 | flat |
| Australia | 10 | flat |
| Belarus | 10 | flat |
| Bulgaria | 10 | flat |
| Estonia | 10 | flat |

> Full per-country breakdown (16 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/jurassic-giants-b7/
- **Public page:** https://i-gaming.tools/slot-games/jurassic-giants-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
