# Country Farming

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/country-farming-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/country-farming-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/country-farming-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/country-farming-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/country-farming-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "country-farming-b7",
  "name": "Country Farming",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.07",
  "rtp_variants": [
    {
      "rtp": "96.07",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.06",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2023-06-12",
  "themes": [
    {
      "slug": "farm",
      "name": "Farm"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "mystery_symbol",
      "name": "Mystery Symbol"
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
      "page_url": "https://i-gaming.tools/slot-games/country-farming-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/country-farming-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/country-farming-b7/demand/
```

**12-month volume (illustrative):** 1,010 · **trend:** declining · YoY -28.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Australia | 120 | flat |
| Brazil | 110 | flat |
| Greece | 100 | growing |
| Canada | 60 | flat |
| Chile | 60 | flat |
| Turkey | 50 | declining |
| United Kingdom | 50 | flat |
| Argentina | 40 | flat |
| Cyprus | 40 | flat |
| Germany | 40 | growing |

> Full per-country breakdown (29 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/country-farming-b7/
- **Public page:** https://i-gaming.tools/slot-games/country-farming-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
