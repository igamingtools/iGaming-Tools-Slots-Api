# Year of the Dragon King

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/year-of-the-dragon-king-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/year-of-the-dragon-king-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/year-of-the-dragon-king-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/year-of-the-dragon-king-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/year-of-the-dragon-king-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "year-of-the-dragon-king-b7",
  "name": "Year of the Dragon King",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.08",
  "rtp_variants": [
    {
      "rtp": "96.08",
      "variant": "default",
      "is_default": true
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
      "label": "Green Dragons",
      "cost": "60.00",
      "is_default": true
    },
    {
      "label": "Random Dragons",
      "cost": "100.00",
      "is_default": false
    }
  ],
  "release_date": "2024-01-15",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "dragons",
      "name": "Dragons"
    },
    {
      "slug": "lions",
      "name": "Lions"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
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
      "page_url": "https://i-gaming.tools/slot-games/year-of-the-dragon-king-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  }
}
```

## Search Demand

`GET /api/v1/slots/year-of-the-dragon-king-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/year-of-the-dragon-king-b7/demand/
```

**12-month volume (illustrative):** 940 · **trend:** declining · YoY -36.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 120 | flat |
| Greece | 100 | declining |
| Philippines | 70 | flat |
| United Kingdom | 70 | growing |
| United States | 60 | flat |
| Germany | 50 | growing |
| Canada | 40 | flat |
| Argentina | 30 | flat |
| Indonesia | 30 | flat |
| Romania | 30 | flat |

> Full per-country breakdown (31 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/year-of-the-dragon-king-b7/
- **Public page:** https://i-gaming.tools/slot-games/year-of-the-dragon-king-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
