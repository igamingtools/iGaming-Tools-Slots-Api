# Mystery of the Nile

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mystery-of-the-nile-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mystery-of-the-nile-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mystery-of-the-nile-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mystery-of-the-nile-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mystery-of-the-nile-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mystery-of-the-nile-b28",
  "name": "Mystery of the Nile",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.35",
  "rtp_variants": [
    {
      "rtp": "96.35",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.36",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.43",
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
      "label": "Full-Screen Golden Pharaoh Symbols",
      "cost": "250.00",
      "is_default": true
    },
    {
      "label": "Free Spins, 3 Bonus Symbols -> 8 spins",
      "cost": "92.70",
      "is_default": false
    }
  ],
  "release_date": "2025-01-08",
  "themes": [
    {
      "slug": "egyptian",
      "name": "Egyptian"
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
      "page_url": "https://i-gaming.tools/slot-games/mystery-of-the-nile-b28/"
    }
  },
  "series": {
    "slug": "mystery",
    "name": "Mystery"
  }
}
```

## Search Demand

`GET /api/v1/slots/mystery-of-the-nile-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mystery-of-the-nile-b28/demand/
```

**12-month volume (illustrative):** 2,300 · **trend:** declining · YoY -8.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 250 | declining |
| Switzerland | 180 | declining |
| Denmark | 150 | declining |
| Greece | 130 | flat |
| Finland | 120 | declining |
| United States | 120 | declining |
| Netherlands | 110 | growing |
| Sweden | 110 | flat |
| United Kingdom | 110 | growing |
| Canada | 100 | flat |

> Full per-country breakdown (38 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mystery-of-the-nile-b28/
- **Public page:** https://i-gaming.tools/slot-games/mystery-of-the-nile-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
