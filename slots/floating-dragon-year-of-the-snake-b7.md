# Floating Dragon – Year of the Snake

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/floating-dragon-year-of-the-snake-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/floating-dragon-year-of-the-snake-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/floating-dragon-year-of-the-snake-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/floating-dragon-year-of-the-snake-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/floating-dragon-year-of-the-snake-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "floating-dragon-year-of-the-snake-b7",
  "name": "Floating Dragon – Year of the Snake",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.71",
  "rtp_variants": [
    {
      "rtp": "96.71",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.71",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.71",
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
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2025-01-13",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "dragons",
      "name": "Dragons"
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
      "page_url": "https://i-gaming.tools/slot-games/floating-dragon-year-of-the-snake-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  },
  "series": {
    "slug": "floating-dragon",
    "name": "Floating Dragon"
  }
}
```

## Search Demand

`GET /api/v1/slots/floating-dragon-year-of-the-snake-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/floating-dragon-year-of-the-snake-b7/demand/
```

**12-month volume (illustrative):** 2,220 · **trend:** growing · YoY +10.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 200 | flat |
| United Kingdom | 140 | growing |
| Brazil | 130 | flat |
| Switzerland | 120 | declining |
| Australia | 110 | growing |
| Spain | 110 | declining |
| Greece | 100 | flat |
| Indonesia | 80 | declining |
| Netherlands | 80 | flat |
| Portugal | 80 | flat |

> Full per-country breakdown (45 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/floating-dragon-year-of-the-snake-b7/
- **Public page:** https://i-gaming.tools/slot-games/floating-dragon-year-of-the-snake-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
