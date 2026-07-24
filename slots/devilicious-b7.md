# Devilicious

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/devilicious-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/devilicious-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/devilicious-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/devilicious-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/devilicious-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "devilicious-b7",
  "name": "Devilicious",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.46",
  "rtp_variants": [
    {
      "rtp": "96.46",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.43",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.52",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2024-06-10",
  "themes": [
    {
      "slug": "devils",
      "name": "Devils"
    },
    {
      "slug": "fire",
      "name": "Fire"
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
      "page_url": "https://i-gaming.tools/slot-games/devilicious-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/devilicious-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/devilicious-b7/demand/
```

**12-month volume (illustrative):** 1,900 · **trend:** declining · YoY -18.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 180 | flat |
| Switzerland | 150 | flat |
| Indonesia | 130 | flat |
| Canada | 120 | flat |
| Greece | 120 | growing |
| Germany | 110 | flat |
| Philippines | 110 | declining |
| United Kingdom | 80 | flat |
| Slovakia | 70 | flat |
| United States | 60 | declining |

> Full per-country breakdown (42 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/devilicious-b7/
- **Public page:** https://i-gaming.tools/slot-games/devilicious-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
