# Mummy's Jewels 100

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mummy-s-jewels-100-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mummy-s-jewels-100-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mummy-s-jewels-100-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mummy-s-jewels-100-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mummy-s-jewels-100-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mummy-s-jewels-100-b7",
  "name": "Mummy's Jewels 100",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.49",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Respins",
      "cost": "50.00",
      "is_default": true
    },
    {
      "label": "Super Bonus",
      "cost": "200.00",
      "is_default": false
    }
  ],
  "release_date": "2026-02-23",
  "themes": [
    {
      "slug": "egyptian",
      "name": "Egyptian"
    },
    {
      "slug": "gems",
      "name": "Gems"
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
      "page_url": "https://i-gaming.tools/slot-games/mummy-s-jewels-100-b7/"
    }
  },
  "series": {
    "slug": "mummys-jewels",
    "name": "Mummy's Jewels"
  }
}
```

## Search Demand

`GET /api/v1/slots/mummy-s-jewels-100-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mummy-s-jewels-100-b7/demand/
```

**12-month volume (illustrative):** 1,170 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 120 | growing |
| Canada | 100 | flat |
| Greece | 100 | declining |
| United States | 60 | growing |
| Australia | 50 | flat |
| United Kingdom | 50 | flat |
| Finland | 40 | flat |
| Netherlands | 40 | declining |
| New Zealand | 40 | declining |
| Peru | 40 | flat |

> Full per-country breakdown (34 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mummy-s-jewels-100-b7/
- **Public page:** https://i-gaming.tools/slot-games/mummy-s-jewels-100-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
