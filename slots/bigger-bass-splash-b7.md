# Bigger Bass Splash

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/bigger-bass-splash-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/bigger-bass-splash-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/bigger-bass-splash-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/bigger-bass-splash-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/bigger-bass-splash-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "bigger-bass-splash-b7",
  "name": "Bigger Bass Splash",
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
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.50",
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
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins",
      "cost": "350.00",
      "is_default": false
    }
  ],
  "release_date": "2025-02-01",
  "themes": [
    {
      "slug": "fishing",
      "name": "Fishing"
    },
    {
      "slug": "ocean",
      "name": "Ocean"
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
      "page_url": "https://i-gaming.tools/slot-games/bigger-bass-splash-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  },
  "series": {
    "slug": "big-bass",
    "name": "Big Bass"
  }
}
```

## Search Demand

`GET /api/v1/slots/bigger-bass-splash-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/bigger-bass-splash-b7/demand/
```

**12-month volume (illustrative):** 230,930 · **trend:** declining · YoY -20.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 68,500 | declining |
| Brazil | 44,700 | declining |
| Greece | 23,600 | declining |
| Germany | 12,000 | declining |
| Netherlands | 9,220 | declining |
| Canada | 7,860 | declining |
| Turkey | 6,210 | declining |
| Spain | 5,200 | declining |
| Romania | 4,800 | declining |
| Italy | 3,940 | declining |

> Full per-country breakdown (63 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/bigger-bass-splash-b7/
- **Public page:** https://i-gaming.tools/slot-games/bigger-bass-splash-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
