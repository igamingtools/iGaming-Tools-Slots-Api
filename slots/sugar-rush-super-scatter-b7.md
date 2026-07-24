# Sugar Rush Super Scatter

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/sugar-rush-super-scatter-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sugar-rush-super-scatter-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/sugar-rush-super-scatter-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/sugar-rush-super-scatter-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/sugar-rush-super-scatter-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "sugar-rush-super-scatter-b7",
  "name": "Sugar Rush Super Scatter",
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
      "rtp": "96.56",
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
  "mechanic": "cluster",
  "reels": 7,
  "rows": 7,
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
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2026-01-15",
  "themes": [
    {
      "slug": "food",
      "name": "Food"
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
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/sugar-rush-super-scatter-b7/"
    }
  },
  "series": {
    "slug": "sugar-rush",
    "name": "Sugar Rush"
  }
}
```

## Search Demand

`GET /api/v1/slots/sugar-rush-super-scatter-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sugar-rush-super-scatter-b7/demand/
```

**12-month volume (illustrative):** 79,170 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 11,780 | declining |
| Philippines | 7,790 | declining |
| Canada | 6,160 | declining |
| Brazil | 6,140 | declining |
| Netherlands | 3,900 | declining |
| Denmark | 3,070 | declining |
| United Kingdom | 2,800 | declining |
| Malaysia | 2,720 | declining |
| Indonesia | 2,700 | declining |
| Italy | 1,890 | declining |

> Full per-country breakdown (62 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/sugar-rush-super-scatter-b7/
- **Public page:** https://i-gaming.tools/slot-games/sugar-rush-super-scatter-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
