# Temple Guardians

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/temple-guardians-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/temple-guardians-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/temple-guardians-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/temple-guardians-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/temple-guardians-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "temple-guardians-b7",
  "name": "Temple Guardians",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.53",
  "rtp_variants": [
    {
      "rtp": "96.53",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.56",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Respins",
      "cost": "70.00",
      "is_default": true
    }
  ],
  "release_date": "2025-06-12",
  "themes": [
    {
      "slug": "adventure",
      "name": "Adventure"
    },
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "fantasy",
      "name": "Fantasy"
    }
  ],
  "features": [
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    },
    {
      "slug": "wild",
      "name": "Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/temple-guardians-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/temple-guardians-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/temple-guardians-b7/demand/
```

**12-month volume (illustrative):** 1,720 · **trend:** growing · YoY +152.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 320 | declining |
| Greece | 160 | flat |
| Romania | 90 | flat |
| Peru | 70 | flat |
| Finland | 60 | flat |
| Malaysia | 60 | flat |
| Mexico | 60 | declining |
| Philippines | 60 | flat |
| United Kingdom | 60 | declining |
| United States | 60 | flat |

> Full per-country breakdown (39 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/temple-guardians-b7/
- **Public page:** https://i-gaming.tools/slot-games/temple-guardians-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
