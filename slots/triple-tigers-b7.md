# Triple Tigers

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/triple-tigers-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/triple-tigers-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/triple-tigers-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/triple-tigers-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/triple-tigers-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "triple-tigers-b7",
  "name": "Triple Tigers",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "97.52",
  "rtp_variants": [
    {
      "rtp": "97.52",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2018-02-01",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "classic",
      "name": "Classic"
    }
  ],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/triple-tigers-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/triple-tigers-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/triple-tigers-b7/demand/
```

**12-month volume (illustrative):** 870 · **trend:** declining · YoY -17.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 140 | flat |
| India | 80 | flat |
| Peru | 50 | declining |
| Netherlands | 40 | flat |
| Philippines | 40 | flat |
| Romania | 40 | declining |
| Turkey | 40 | flat |
| Germany | 30 | growing |
| Greece | 30 | flat |
| Switzerland | 30 | flat |

> Full per-country breakdown (34 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/triple-tigers-b7/
- **Public page:** https://i-gaming.tools/slot-games/triple-tigers-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
