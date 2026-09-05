# Masked Mayhem

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/masked-mayhem-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/masked-mayhem-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/masked-mayhem-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/masked-mayhem-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/masked-mayhem-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "masked-mayhem-b28",
  "name": "Masked Mayhem",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.29",
  "rtp_variants": [
    {
      "rtp": "96.29",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.33",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Random Bonus Symbols",
      "cost": "60.00",
      "is_default": true
    }
  ],
  "release_date": "2025-10-01",
  "themes": [
    {
      "slug": "day-of-the-dead",
      "name": "Day of the Dead"
    },
    {
      "slug": "mexican",
      "name": "Mexican"
    },
    {
      "slug": "wrestling",
      "name": "Wrestling"
    }
  ],
  "features": [
    {
      "slug": "collector-zone",
      "name": "Collector Zone"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "level-progression",
      "name": "Level Progression"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/masked-mayhem-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/masked-mayhem-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/masked-mayhem-b28/demand/
```

**12-month volume (illustrative):** 1,980 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 150 | flat |
| Canada | 120 | flat |
| Greece | 120 | flat |
| Netherlands | 110 | flat |
| Australia | 100 | flat |
| Brazil | 100 | flat |
| Germany | 100 | flat |
| Latvia | 100 | growing |
| Denmark | 90 | flat |
| United States | 80 | growing |

> Full per-country breakdown (47 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/masked-mayhem-b28/
- **Public page:** https://i-gaming.tools/slot-games/masked-mayhem-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
