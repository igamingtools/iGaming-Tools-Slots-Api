# Wild Booster

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wild-booster-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-booster-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wild-booster-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wild-booster-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wild-booster-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wild-booster-b7",
  "name": "Wild Booster",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.47",
  "rtp_variants": [
    {
      "rtp": "96.47",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.47",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "75.00",
      "is_default": true
    }
  ],
  "release_date": "2021-04-01",
  "themes": [
    {
      "slug": "classic",
      "name": "Classic"
    },
    {
      "slug": "fruits",
      "name": "Fruits"
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
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/wild-booster-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/wild-booster-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-booster-b7/demand/
```

**12-month volume (illustrative):** 1,480 · **trend:** declining · YoY -21.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 120 | flat |
| United States | 120 | declining |
| Romania | 100 | flat |
| Germany | 80 | growing |
| Lithuania | 80 | flat |
| Malaysia | 80 | flat |
| Canada | 60 | flat |
| Greece | 60 | flat |
| Indonesia | 60 | flat |
| Turkey | 60 | flat |

> Full per-country breakdown (38 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wild-booster-b7/
- **Public page:** https://i-gaming.tools/slot-games/wild-booster-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
