# Fire Hopper

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fire-hopper-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fire-hopper-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fire-hopper-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fire-hopper-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fire-hopper-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fire-hopper-b28",
  "name": "Fire Hopper",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.30",
  "rtp_variants": [
    {
      "rtp": "96.30",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.38",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 7,
  "rows": 7,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Games Feature",
      "cost": "124.00",
      "is_default": true
    }
  ],
  "release_date": "2021-12-07",
  "themes": [
    {
      "slug": "fire",
      "name": "Fire"
    },
    {
      "slug": "flowers",
      "name": "Flowers"
    },
    {
      "slug": "frogs",
      "name": "Frogs"
    }
  ],
  "features": [
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
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
      "page_url": "https://i-gaming.tools/slot-games/fire-hopper-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fire-hopper-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fire-hopper-b28/demand/
```

**12-month volume (illustrative):** 3,930 · **trend:** declining · YoY -21.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Switzerland | 330 | flat |
| Germany | 320 | flat |
| Finland | 220 | flat |
| Greece | 170 | flat |
| Canada | 160 | flat |
| Ukraine | 160 | flat |
| United States | 160 | flat |
| Denmark | 150 | flat |
| Austria | 140 | flat |
| United Kingdom | 140 | declining |

> Full per-country breakdown (52 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fire-hopper-b28/
- **Public page:** https://i-gaming.tools/slot-games/fire-hopper-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
