# Wildies

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wildies-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wildies-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wildies-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wildies-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wildies-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wildies-b7",
  "name": "Wildies",
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
    },
    {
      "rtp": "96.00",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "80.00",
      "is_default": true
    }
  ],
  "release_date": "2024-05-01",
  "themes": [
    {
      "slug": "food",
      "name": "Food"
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
      "slug": "respin",
      "name": "Respin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/wildies-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/wildies-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wildies-b7/demand/
```

**12-month volume (illustrative):** 2,930 · **trend:** declining · YoY -16.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Philippines | 490 | declining |
| Greece | 430 | declining |
| Brazil | 190 | declining |
| Canada | 100 | flat |
| Germany | 90 | declining |
| Netherlands | 90 | declining |
| Switzerland | 90 | declining |
| Malaysia | 80 | flat |
| Peru | 80 | declining |
| Portugal | 80 | declining |

> Full per-country breakdown (47 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wildies-b7/
- **Public page:** https://i-gaming.tools/slot-games/wildies-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
