# Fat banker

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fat-banker-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fat-banker-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fat-banker-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fat-banker-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fat-banker-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fat-banker-b28",
  "name": "Fat banker",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.43",
  "rtp_variants": [
    {
      "rtp": "96.43",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.63",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.65",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 6,
  "rows": 6,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Fortune Link Feature",
      "cost": "30.00",
      "is_default": true
    },
    {
      "label": "Fat Banker Free Spins Feature - Random Scatters",
      "cost": "150.00",
      "is_default": false
    }
  ],
  "release_date": "2022-05-19",
  "themes": [
    {
      "slug": "luxury",
      "name": "Luxury"
    },
    {
      "slug": "money",
      "name": "Money"
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
      "page_url": "https://i-gaming.tools/slot-games/fat-banker-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fat-banker-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fat-banker-b28/demand/
```

**12-month volume (illustrative):** 11,820 · **trend:** declining · YoY -18.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 2,670 | declining |
| Greece | 1,110 | growing |
| Finland | 600 | growing |
| Sweden | 570 | growing |
| Switzerland | 540 | flat |
| Denmark | 460 | flat |
| Austria | 310 | flat |
| United Kingdom | 280 | declining |
| Norway | 270 | flat |
| Canada | 260 | flat |

> Full per-country breakdown (63 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fat-banker-b28/
- **Public page:** https://i-gaming.tools/slot-games/fat-banker-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
