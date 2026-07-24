# Oodles of Noodles

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/oodles-of-noodles-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/oodles-of-noodles-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/oodles-of-noodles-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/oodles-of-noodles-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/oodles-of-noodles-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "oodles-of-noodles-b7",
  "name": "Oodles of Noodles",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.58",
  "rtp_variants": [
    {
      "rtp": "96.58",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.58",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.58",
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
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2024-09-23",
  "themes": [
    {
      "slug": "asian",
      "name": "Asian"
    },
    {
      "slug": "food",
      "name": "Food"
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
      "slug": "expanding-symbols",
      "name": "Expanding Symbols"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/oodles-of-noodles-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  }
}
```

## Search Demand

`GET /api/v1/slots/oodles-of-noodles-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/oodles-of-noodles-b7/demand/
```

**12-month volume (illustrative):** 1,400 · **trend:** declining · YoY -39.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 160 | flat |
| Brazil | 110 | declining |
| Greece | 100 | declining |
| United Kingdom | 90 | flat |
| Finland | 80 | flat |
| Denmark | 70 | declining |
| Lithuania | 70 | flat |
| Germany | 50 | growing |
| Indonesia | 50 | flat |
| Philippines | 50 | flat |

> Full per-country breakdown (38 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/oodles-of-noodles-b7/
- **Public page:** https://i-gaming.tools/slot-games/oodles-of-noodles-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
