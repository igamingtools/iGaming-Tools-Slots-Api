# Henry The Ape

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/henry-the-ape-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/henry-the-ape-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/henry-the-ape-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/henry-the-ape-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/henry-the-ape-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "henry-the-ape-b28",
  "name": "Henry The Ape",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.44",
  "rtp_variants": [
    {
      "rtp": "96.44",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.32",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.30",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Random Free Spins",
      "cost": "179.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins",
      "cost": "425.00",
      "is_default": false
    }
  ],
  "release_date": "2025-06-11",
  "themes": [
    {
      "slug": "monkeys",
      "name": "Monkeys"
    },
    {
      "slug": "music",
      "name": "Music"
    },
    {
      "slug": "urban",
      "name": "Urban"
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
      "page_url": "https://i-gaming.tools/slot-games/henry-the-ape-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/henry-the-ape-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/henry-the-ape-b28/demand/
```

**12-month volume (illustrative):** 1,580 · **trend:** growing · YoY +77.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 160 | declining |
| Greece | 140 | declining |
| Netherlands | 130 | declining |
| Switzerland | 120 | flat |
| Sweden | 110 | flat |
| Finland | 80 | flat |
| Germany | 80 | growing |
| United Kingdom | 80 | flat |
| United States | 80 | flat |
| Denmark | 70 | declining |

> Full per-country breakdown (40 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/henry-the-ape-b28/
- **Public page:** https://i-gaming.tools/slot-games/henry-the-ape-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
