# Himalayan Wild

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/himalayan-wild-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/himalayan-wild-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/himalayan-wild-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/himalayan-wild-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/himalayan-wild-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "himalayan-wild-b7",
  "name": "Himalayan Wild",
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
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Buy Super Free Spins",
      "cost": "300.00",
      "is_default": false
    }
  ],
  "release_date": "2024-11-11",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "mountains",
      "name": "Mountains"
    },
    {
      "slug": "winter",
      "name": "Winter"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/himalayan-wild-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/himalayan-wild-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/himalayan-wild-b7/demand/
```

**12-month volume (illustrative):** 1,130 · **trend:** declining · YoY -46.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Malaysia | 120 | growing |
| Greece | 110 | declining |
| Brazil | 90 | declining |
| Philippines | 80 | flat |
| Canada | 60 | flat |
| Lithuania | 60 | flat |
| Switzerland | 60 | flat |
| Bulgaria | 40 | declining |
| Germany | 40 | flat |
| India | 40 | growing |

> Full per-country breakdown (30 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/himalayan-wild-b7/
- **Public page:** https://i-gaming.tools/slot-games/himalayan-wild-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
