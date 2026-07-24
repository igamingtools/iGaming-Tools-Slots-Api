# Santa's Xmas Rush

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/santa-s-xmas-rush-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/santa-s-xmas-rush-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/santa-s-xmas-rush-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/santa-s-xmas-rush-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/santa-s-xmas-rush-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "santa-s-xmas-rush-b7",
  "name": "Santa's Xmas Rush",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.51",
  "rtp_variants": [
    {
      "rtp": "96.51",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.50",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.52",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 6,
  "rows": 6,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "120.00",
      "is_default": true
    }
  ],
  "release_date": "2024-11-28",
  "themes": [
    {
      "slug": "christmas",
      "name": "Christmas"
    },
    {
      "slug": "winter",
      "name": "Winter"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
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
      "page_url": "https://i-gaming.tools/slot-games/santa-s-xmas-rush-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/santa-s-xmas-rush-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/santa-s-xmas-rush-b7/demand/
```

**12-month volume (illustrative):** 680 · **trend:** declining · YoY -38.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 120 | flat |
| Brazil | 70 | declining |
| Greece | 70 | flat |
| Denmark | 50 | flat |
| Belgium | 40 | flat |
| Lithuania | 30 | flat |
| Norway | 30 | flat |
| Philippines | 30 | growing |
| Switzerland | 30 | flat |
| Argentina | 20 | flat |

> Full per-country breakdown (25 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/santa-s-xmas-rush-b7/
- **Public page:** https://i-gaming.tools/slot-games/santa-s-xmas-rush-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
