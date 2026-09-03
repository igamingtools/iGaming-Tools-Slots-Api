# Fang City

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fang-city-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fang-city-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fang-city-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fang-city-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fang-city-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fang-city-b28",
  "name": "Fang City",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.33",
  "rtp_variants": [
    {
      "rtp": "96.33",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.45",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.32",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "scatter_pays",
  "reels": 6,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "X1 multiplier",
      "cost": "50.00",
      "is_default": true
    },
    {
      "label": "Random Free Spins",
      "cost": "150.00",
      "is_default": false
    }
  ],
  "release_date": "2025-06-18",
  "themes": [
    {
      "slug": "cyberpunk",
      "name": "Cyberpunk"
    },
    {
      "slug": "urban",
      "name": "Urban"
    },
    {
      "slug": "wolves",
      "name": "Wolves"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
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
      "page_url": "https://i-gaming.tools/slot-games/fang-city-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fang-city-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fang-city-b28/demand/
```

**12-month volume (illustrative):** 1,220 · **trend:** growing · YoY +28.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 140 | declining |
| Brazil | 100 | flat |
| Greece | 90 | flat |
| Sweden | 90 | declining |
| Canada | 80 | growing |
| Latvia | 70 | flat |
| India | 60 | flat |
| New Zealand | 60 | declining |
| Switzerland | 60 | flat |
| Netherlands | 50 | flat |

> Full per-country breakdown (28 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fang-city-b28/
- **Public page:** https://i-gaming.tools/slot-games/fang-city-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
