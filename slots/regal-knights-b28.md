# Regal Knights

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/regal-knights-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/regal-knights-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/regal-knights-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/regal-knights-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/regal-knights-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "regal-knights-b28",
  "name": "Regal Knights",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.22",
  "rtp_variants": [
    {
      "rtp": "96.22",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.33",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.38",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "low",
  "mechanic": "lines",
  "reels": 5,
  "rows": 6,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Random Scatters",
      "cost": "60.00",
      "is_default": true
    }
  ],
  "release_date": "2025-05-28",
  "themes": [
    {
      "slug": "medieval",
      "name": "Medieval"
    },
    {
      "slug": "royalty",
      "name": "Royalty"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
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
      "page_url": "https://i-gaming.tools/slot-games/regal-knights-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/regal-knights-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/regal-knights-b28/demand/
```

**12-month volume (illustrative):** 1,510 · **trend:** growing · YoY +38.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 200 | flat |
| Finland | 160 | flat |
| Greece | 160 | flat |
| Latvia | 90 | declining |
| Netherlands | 80 | flat |
| United Kingdom | 80 | declining |
| United States | 80 | flat |
| Sweden | 70 | flat |
| Croatia | 40 | flat |
| Germany | 40 | flat |

> Full per-country breakdown (33 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/regal-knights-b28/
- **Public page:** https://i-gaming.tools/slot-games/regal-knights-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
