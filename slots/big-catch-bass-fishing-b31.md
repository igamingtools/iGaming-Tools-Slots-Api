# Big Catch Bass Fishing

**Provider:** Blueprint Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/big-catch-bass-fishing-b31/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-catch-bass-fishing-b31/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/big-catch-bass-fishing-b31/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/big-catch-bass-fishing-b31/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/big-catch-bass-fishing-b31/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "big-catch-bass-fishing-b31",
  "name": "Big Catch Bass Fishing",
  "status": "active",
  "provider": {
    "slug": "blueprint-gaming",
    "name": "Blueprint Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "95.00",
  "rtp_variants": [
    {
      "rtp": "95.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "95.00",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "93.00",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "med_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "The Big Catch Bonus Guaranteed",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2023-06-01",
  "themes": [
    {
      "slug": "fishing",
      "name": "Fishing"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/big-catch-bass-fishing-b31/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/big-catch-bass-fishing-b31/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-catch-bass-fishing-b31/demand/
```

**12-month volume (illustrative):** 2,140 · **trend:** growing · YoY +9.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 720 | flat |
| United Kingdom | 320 | declining |
| Canada | 180 | flat |
| Ireland | 100 | flat |
| South Africa | 100 | flat |
| Indonesia | 70 | flat |
| Italy | 70 | flat |
| Finland | 60 | flat |
| Greece | 60 | declining |
| Netherlands | 50 | flat |

> Full per-country breakdown (28 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/big-catch-bass-fishing-b31/
- **Public page:** https://i-gaming.tools/slot-games/big-catch-bass-fishing-b31/
- **Full schema:** https://i-gaming.tools/api/docs/
