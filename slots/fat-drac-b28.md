# Fat Drac

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fat-drac-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fat-drac-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fat-drac-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fat-drac-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fat-drac-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fat-drac-b28",
  "name": "Fat Drac",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.57",
  "rtp_variants": [
    {
      "rtp": "96.57",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "94.05",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2021-10-14",
  "themes": [
    {
      "slug": "halloween",
      "name": "Halloween"
    },
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "vampires",
      "name": "Vampires"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "giant-symbol",
      "name": "Giant Symbol"
    },
    {
      "slug": "pick_bonus",
      "name": "Pick Bonus"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/fat-drac-b28/"
    }
  },
  "series": {
    "slug": "fat",
    "name": "Fat"
  }
}
```

## Search Demand

`GET /api/v1/slots/fat-drac-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fat-drac-b28/demand/
```

**12-month volume (illustrative):** 1,800 · **trend:** declining · YoY -7.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Switzerland | 240 | declining |
| Germany | 170 | flat |
| Finland | 120 | declining |
| Romania | 110 | declining |
| United Kingdom | 110 | flat |
| Austria | 100 | declining |
| Sweden | 100 | flat |
| Greece | 90 | declining |
| Canada | 80 | flat |
| Netherlands | 80 | flat |

> Full per-country breakdown (35 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fat-drac-b28/
- **Public page:** https://i-gaming.tools/slot-games/fat-drac-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
