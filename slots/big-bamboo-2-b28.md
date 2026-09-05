# Big Bamboo 2

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/big-bamboo-2-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-bamboo-2-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/big-bamboo-2-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/big-bamboo-2-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/big-bamboo-2-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "big-bamboo-2-b28",
  "name": "Big Bamboo 2",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.36",
  "rtp_variants": [
    {
      "rtp": "96.36",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.33",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.07",
      "variant": "feature",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 5,
  "rows": 6,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Mystery Bamboo Symbols",
      "cost": "5.00",
      "is_default": true
    },
    {
      "label": "Golden Bamboo Feature",
      "cost": "250.00",
      "is_default": false
    }
  ],
  "release_date": "2026-03-25",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "fantasy",
      "name": "Fantasy"
    },
    {
      "slug": "panda",
      "name": "Panda"
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
      "slug": "gamble",
      "name": "Gamble"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/big-bamboo-2-b28/"
    }
  },
  "series": {
    "slug": "bamboo-series",
    "name": "Bamboo Series"
  }
}
```

## Search Demand

`GET /api/v1/slots/big-bamboo-2-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-bamboo-2-b28/demand/
```

**12-month volume (illustrative):** 12,770 · **trend:** growing · YoY +2403.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Sweden | 1,620 | flat |
| Germany | 1,130 | flat |
| Netherlands | 1,110 | declining |
| Finland | 1,000 | declining |
| United Kingdom | 900 | declining |
| Greece | 670 | declining |
| Latvia | 650 | declining |
| Canada | 520 | declining |
| Austria | 450 | declining |
| Italy | 440 | growing |

> Full per-country breakdown (61 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/big-bamboo-2-b28/
- **Public page:** https://i-gaming.tools/slot-games/big-bamboo-2-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
