# Shamrock Saints

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/shamrock-saints-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/shamrock-saints-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/shamrock-saints-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/shamrock-saints-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/shamrock-saints-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "shamrock-saints-b28",
  "name": "Shamrock Saints",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.66",
  "rtp_variants": [
    {
      "rtp": "96.66",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.81",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.37",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "3 Scatters",
      "cost": "56.00",
      "is_default": true
    },
    {
      "label": "4 Scatters",
      "cost": "111.00",
      "is_default": false
    }
  ],
  "release_date": "2024-03-05",
  "themes": [
    {
      "slug": "irish",
      "name": "Irish"
    },
    {
      "slug": "mafia",
      "name": "Mafia"
    },
    {
      "slug": "urban",
      "name": "Urban"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "level-progression",
      "name": "Level Progression"
    },
    {
      "slug": "mystery_symbol",
      "name": "Mystery Symbol"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/shamrock-saints-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/shamrock-saints-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/shamrock-saints-b28/demand/
```

**12-month volume (illustrative):** 1,370 · **trend:** declining · YoY -29.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 130 | flat |
| Sweden | 100 | declining |
| United Kingdom | 100 | growing |
| Denmark | 90 | declining |
| Netherlands | 90 | declining |
| Canada | 80 | flat |
| United States | 80 | declining |
| Finland | 60 | flat |
| Brazil | 50 | declining |
| Ireland | 50 | declining |

> Full per-country breakdown (33 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/shamrock-saints-b28/
- **Public page:** https://i-gaming.tools/slot-games/shamrock-saints-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
