# Wild Heart

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wild-heart-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-heart-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wild-heart-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wild-heart-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wild-heart-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wild-heart-b10",
  "name": "Wild Heart",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.92",
  "rtp_variants": [
    {
      "rtp": "96.92",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.02",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "97.03",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Bonus - Regular",
      "cost": "50.00",
      "is_default": true
    },
    {
      "label": "Buy Bonus - With 2x2 Wilds",
      "cost": "120.00",
      "is_default": false
    }
  ],
  "release_date": "2024-01-25",
  "themes": [
    {
      "slug": "romance",
      "name": "Romance"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    },
    {
      "slug": "sticky_wild",
      "name": "Sticky Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/wild-heart-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/wild-heart-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-heart-b10/demand/
```

**12-month volume (illustrative):** 1,500 · **trend:** growing · YoY +11.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 480 | flat |
| Canada | 220 | declining |
| Germany | 130 | declining |
| United Kingdom | 120 | flat |
| Australia | 100 | declining |
| France | 100 | flat |
| Switzerland | 90 | flat |
| Finland | 60 | flat |
| Austria | 50 | flat |
| Belgium | 40 | flat |

> Full per-country breakdown (16 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wild-heart-b10/
- **Public page:** https://i-gaming.tools/slot-games/wild-heart-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
