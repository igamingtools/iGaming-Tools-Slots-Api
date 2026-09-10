# Wild Trucks

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wild-trucks-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-trucks-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wild-trucks-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wild-trucks-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wild-trucks-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wild-trucks-b29",
  "name": "Wild Trucks",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.65",
  "rtp_variants": [
    {
      "rtp": "96.65",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "progressive",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2019-06-25",
  "themes": [
    {
      "slug": "road-trip",
      "name": "Road Trip"
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
      "slug": "symbol-transform",
      "name": "Symbol Transform"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/wild-trucks-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/wild-trucks-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-trucks-b29/demand/
```

**12-month volume (illustrative):** 21,130 · **trend:** declining · YoY -24.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 17,100 | flat |
| Lithuania | 1,460 | growing |
| United States | 500 | flat |
| Canada | 280 | declining |
| India | 160 | declining |
| United Kingdom | 140 | growing |
| Pakistan | 100 | flat |
| Indonesia | 80 | declining |
| New Zealand | 80 | flat |
| Brazil | 70 | flat |

> Full per-country breakdown (56 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wild-trucks-b29/
- **Public page:** https://i-gaming.tools/slot-games/wild-trucks-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
