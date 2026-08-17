# Aviamasters 2

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/aviamasters-2-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/aviamasters-2-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/aviamasters-2-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/aviamasters-2-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/aviamasters-2-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "aviamasters-2-b10",
  "name": "Aviamasters 2",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "crash",
  "rtp_default": "97.00",
  "rtp_variants": [
    {
      "rtp": "97.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "med_low",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Safe Landing",
      "cost": "50.00",
      "is_default": true
    }
  ],
  "release_date": "2026-03-05",
  "themes": [
    {
      "slug": "aviation",
      "name": "Aviation"
    }
  ],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/aviamasters-2-b10/"
    }
  },
  "series": {
    "slug": "aviamasters",
    "name": "Aviamasters"
  }
}
```

## Search Demand

`GET /api/v1/slots/aviamasters-2-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/aviamasters-2-b10/demand/
```

**12-month volume (illustrative):** 2,280 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 120 | declining |
| Germany | 120 | declining |
| United States | 100 | declining |
| Vietnam | 100 | declining |
| United Kingdom | 90 | declining |
| Canada | 80 | declining |
| India | 80 | declining |
| Pakistan | 80 | flat |
| Switzerland | 60 | declining |
| Argentina | 50 | declining |

> Full per-country breakdown (57 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/aviamasters-2-b10/
- **Public page:** https://i-gaming.tools/slot-games/aviamasters-2-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
