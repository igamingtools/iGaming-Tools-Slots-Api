# Chicken Route

**Provider:** Turbo Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/chicken-route-b27/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chicken-route-b27/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/chicken-route-b27/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/chicken-route-b27/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/chicken-route-b27/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "chicken-route-b27",
  "name": "Chicken Route",
  "status": "active",
  "provider": {
    "slug": "turbo-games",
    "name": "Turbo Games"
  },
  "game_category": "crash",
  "rtp_default": "96.00",
  "rtp_variants": [
    {
      "rtp": "96.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-10-01",
  "themes": [
    {
      "slug": "farm",
      "name": "Farm"
    }
  ],
  "features": [
    {
      "slug": "cash-out",
      "name": "Cash Out"
    },
    {
      "slug": "level-progression",
      "name": "Level Progression"
    },
    {
      "slug": "variable_volatility",
      "name": "Variable Volatility"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/chicken-route-b27/"
    }
  },
  "series": {
    "slug": "chicken",
    "name": "Chicken"
  }
}
```

## Search Demand

`GET /api/v1/slots/chicken-route-b27/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chicken-route-b27/demand/
```

**12-month volume (illustrative):** 2,060 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 340 | growing |
| India | 240 | flat |
| Pakistan | 120 | flat |
| Ghana | 90 | flat |
| Canada | 80 | declining |
| Germany | 70 | flat |
| Tunisia | 70 | flat |
| Netherlands | 60 | flat |
| Poland | 60 | declining |
| Ukraine | 60 | growing |

> Full per-country breakdown (44 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/chicken-route-b27/
- **Public page:** https://i-gaming.tools/slot-games/chicken-route-b27/
- **Full schema:** https://i-gaming.tools/api/docs/
