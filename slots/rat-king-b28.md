# Rat King

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/rat-king-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rat-king-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/rat-king-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/rat-king-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/rat-king-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "rat-king-b28",
  "name": "Rat King",
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
      "rtp": "96.34",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.58",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "cluster",
  "reels": 6,
  "rows": 6,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "3 Scatters",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "4 Scatters",
      "cost": "250.00",
      "is_default": false
    }
  ],
  "release_date": "2023-07-27",
  "themes": [
    {
      "slug": "arcade",
      "name": "Arcade"
    },
    {
      "slug": "rats",
      "name": "Rats"
    },
    {
      "slug": "sweets",
      "name": "Sweets"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/rat-king-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/rat-king-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rat-king-b28/demand/
```

**12-month volume (illustrative):** 1,700 · **trend:** growing · YoY +16.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 440 | flat |
| Finland | 240 | flat |
| Greece | 120 | flat |
| Netherlands | 110 | flat |
| Denmark | 100 | flat |
| United Kingdom | 80 | flat |
| United States | 80 | flat |
| Brazil | 70 | growing |
| Bulgaria | 50 | flat |
| Romania | 50 | flat |

> Full per-country breakdown (31 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/rat-king-b28/
- **Public page:** https://i-gaming.tools/slot-games/rat-king-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
