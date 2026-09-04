# Mad Cars

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mad-cars-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mad-cars-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mad-cars-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mad-cars-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mad-cars-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mad-cars-b28",
  "name": "Mad Cars",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.39",
  "rtp_variants": [
    {
      "rtp": "96.39",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.40",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.46",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Mad Bonus",
      "cost": "115.70",
      "is_default": true
    },
    {
      "label": "Payer Bonus",
      "cost": "301.00",
      "is_default": false
    }
  ],
  "release_date": "2022-08-10",
  "themes": [
    {
      "slug": "post-apocalyptic",
      "name": "Post-Apocalyptic"
    },
    {
      "slug": "road-trip",
      "name": "Road Trip"
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
      "slug": "moving-value-symbols",
      "name": "Moving Value Symbols"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/mad-cars-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/mad-cars-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mad-cars-b28/demand/
```

**12-month volume (illustrative):** 1,930 · **trend:** declining · YoY -20.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 140 | growing |
| Greece | 130 | declining |
| India | 100 | flat |
| Romania | 100 | flat |
| Ukraine | 100 | flat |
| Netherlands | 90 | growing |
| Sweden | 90 | declining |
| Switzerland | 90 | flat |
| Canada | 80 | flat |
| Denmark | 80 | declining |

> Full per-country breakdown (49 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mad-cars-b28/
- **Public page:** https://i-gaming.tools/slot-games/mad-cars-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
