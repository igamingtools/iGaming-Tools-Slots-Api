# Super Serge

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/super-serge-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/super-serge-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/super-serge-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/super-serge-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/super-serge-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "super-serge-b7",
  "name": "Super Serge",
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
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "ways",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "4 Bonuses",
      "cost": "75.00",
      "is_default": true
    },
    {
      "label": "5 Bonuses",
      "cost": "125.00",
      "is_default": false
    }
  ],
  "release_date": "2026-08-06",
  "themes": [
    {
      "slug": "cyberpunk",
      "name": "Cyberpunk"
    },
    {
      "slug": "energy",
      "name": "Energy"
    },
    {
      "slug": "superheroes",
      "name": "Superheroes"
    }
  ],
  "features": [
    {
      "slug": "free-spins-choice",
      "name": "Free Spins Choice"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "growing-reels",
      "name": "Growing Reels"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/super-serge-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/super-serge-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/super-serge-b7/demand/
```

**12-month volume (illustrative):** 320 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 30 | growing |
| Philippines | 30 | growing |
| Belgium | 20 | growing |
| Canada | 20 | growing |
| Finland | 20 | growing |
| Argentina | 10 | growing |
| Australia | 10 | growing |
| Austria | 10 | growing |
| Bulgaria | 10 | growing |
| Denmark | 10 | growing |

> Full per-country breakdown (25 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/super-serge-b7/
- **Public page:** https://i-gaming.tools/slot-games/super-serge-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
