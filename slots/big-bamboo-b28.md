# Big Bamboo

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/big-bamboo-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-bamboo-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/big-bamboo-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/big-bamboo-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/big-bamboo-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "big-bamboo-b28",
  "name": "Big Bamboo",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.13",
  "rtp_variants": [
    {
      "rtp": "96.13",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.94",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.76",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 6,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "No Low Symbols Converted",
      "cost": "99.00",
      "is_default": true
    },
    {
      "label": "2 Low Symbols Converted",
      "cost": "179.00",
      "is_default": false
    }
  ],
  "release_date": "2022-03-03",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "monkeys",
      "name": "Monkeys"
    },
    {
      "slug": "panda",
      "name": "Panda"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "gamble",
      "name": "Gamble"
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
      "page_url": "https://i-gaming.tools/slot-games/big-bamboo-b28/"
    }
  },
  "series": {
    "slug": "bamboo-series",
    "name": "Bamboo Series"
  }
}
```

## Search Demand

`GET /api/v1/slots/big-bamboo-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-bamboo-b28/demand/
```

**12-month volume (illustrative):** 74,650 · **trend:** declining · YoY -16.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 10,070 | declining |
| Ukraine | 6,210 | declining |
| Switzerland | 6,030 | declining |
| United States | 5,080 | flat |
| Greece | 3,780 | growing |
| Sweden | 3,540 | flat |
| United Kingdom | 3,450 | declining |
| Finland | 3,300 | declining |
| Netherlands | 2,850 | declining |
| Italy | 2,460 | flat |

> Full per-country breakdown (78 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/big-bamboo-b28/
- **Public page:** https://i-gaming.tools/slot-games/big-bamboo-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
