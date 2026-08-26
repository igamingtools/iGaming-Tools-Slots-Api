# Razor Shark

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/razor-shark-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/razor-shark-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/razor-shark-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/razor-shark-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/razor-shark-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "razor-shark-b28",
  "name": "Razor Shark",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.70",
  "rtp_variants": [
    {
      "rtp": "96.70",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2019-09-03",
  "themes": [
    {
      "slug": "ocean",
      "name": "Ocean"
    },
    {
      "slug": "sharks",
      "name": "Sharks"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier-spots",
      "name": "Multiplier Spots"
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
      "page_url": "https://i-gaming.tools/slot-games/razor-shark-b28/"
    }
  },
  "series": {
    "slug": "razor",
    "name": "Razor"
  }
}
```

## Search Demand

`GET /api/v1/slots/razor-shark-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/razor-shark-b28/demand/
```

**12-month volume (illustrative):** 63,360 · **trend:** declining · YoY -31.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 39,350 | declining |
| Switzerland | 3,410 | flat |
| Austria | 3,290 | declining |
| Greece | 1,590 | flat |
| Netherlands | 1,550 | declining |
| United Kingdom | 1,410 | declining |
| Finland | 1,380 | declining |
| United States | 1,240 | declining |
| Sweden | 890 | declining |
| Canada | 640 | flat |

> Full per-country breakdown (72 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/razor-shark-b28/
- **Public page:** https://i-gaming.tools/slot-games/razor-shark-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
