# Forge of Olympus

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/forge-of-olympus-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/forge-of-olympus-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/forge-of-olympus-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/forge-of-olympus-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/forge-of-olympus-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "forge-of-olympus-b7",
  "name": "Forge of Olympus",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.25",
  "rtp_variants": [
    {
      "rtp": "96.25",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.23",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.42",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "scatter_pays",
  "reels": 6,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins Level 1",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Buy Free Spins Level 2",
      "cost": "200.00",
      "is_default": false
    }
  ],
  "release_date": "2023-08-17",
  "themes": [
    {
      "slug": "ancient-greece",
      "name": "Ancient Greece"
    },
    {
      "slug": "fire",
      "name": "Fire"
    },
    {
      "slug": "mythology",
      "name": "Mythology"
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
      "page_url": "https://i-gaming.tools/slot-games/forge-of-olympus-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/forge-of-olympus-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/forge-of-olympus-b7/demand/
```

**12-month volume (illustrative):** 16,370 · **trend:** declining · YoY -44.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 6,760 | flat |
| Brazil | 1,230 | flat |
| Philippines | 910 | flat |
| Indonesia | 860 | declining |
| Netherlands | 530 | declining |
| Switzerland | 510 | flat |
| Cyprus | 420 | growing |
| Belgium | 240 | flat |
| Canada | 240 | flat |
| Malaysia | 200 | flat |

> Full per-country breakdown (68 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/forge-of-olympus-b7/
- **Public page:** https://i-gaming.tools/slot-games/forge-of-olympus-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
