# Steamin' Reels

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/steamin-reels-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/steamin-reels-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/steamin-reels-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/steamin-reels-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/steamin-reels-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "steamin-reels-b7",
  "name": "Steamin' Reels",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.53",
  "rtp_variants": [
    {
      "rtp": "96.53",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.52",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.52",
      "variant": "default",
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
  "release_date": "2026-03-19",
  "themes": [
    {
      "slug": "trains",
      "name": "Trains"
    },
    {
      "slug": "western",
      "name": "Western"
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
      "page_url": "https://i-gaming.tools/slot-games/steamin-reels-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  }
}
```

## Search Demand

`GET /api/v1/slots/steamin-reels-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/steamin-reels-b7/demand/
```

**12-month volume (illustrative):** 1,490 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 130 | flat |
| Greece | 100 | flat |
| Canada | 60 | declining |
| Denmark | 60 | declining |
| Malaysia | 60 | flat |
| Philippines | 60 | flat |
| Germany | 50 | flat |
| Netherlands | 50 | declining |
| United Kingdom | 50 | declining |
| Australia | 40 | growing |

> Full per-country breakdown (50 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/steamin-reels-b7/
- **Public page:** https://i-gaming.tools/slot-games/steamin-reels-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
