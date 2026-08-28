# Tiki Tumble

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/tiki-tumble-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/tiki-tumble-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/tiki-tumble-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/tiki-tumble-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/tiki-tumble-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "tiki-tumble-b28",
  "name": "Tiki Tumble",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.49",
  "rtp_variants": [
    {
      "rtp": "96.49",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.91",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.90",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Three Scatters",
      "cost": "95.00",
      "is_default": true
    },
    {
      "label": "Four Scatters",
      "cost": "123.50",
      "is_default": false
    }
  ],
  "release_date": "2018-02-27",
  "themes": [
    {
      "slug": "jungle",
      "name": "Jungle"
    },
    {
      "slug": "tiki",
      "name": "Tiki"
    },
    {
      "slug": "tropical",
      "name": "Tropical"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "nudge",
      "name": "Nudge"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/tiki-tumble-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/tiki-tumble-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/tiki-tumble-b28/demand/
```

**12-month volume (illustrative):** 1,630 · **trend:** declining · YoY -25.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 220 | flat |
| Switzerland | 180 | declining |
| Germany | 150 | flat |
| Canada | 100 | declining |
| Sweden | 90 | declining |
| Denmark | 80 | growing |
| India | 80 | flat |
| United Kingdom | 80 | declining |
| Greece | 60 | flat |
| Netherlands | 60 | flat |

> Full per-country breakdown (36 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/tiki-tumble-b28/
- **Public page:** https://i-gaming.tools/slot-games/tiki-tumble-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
