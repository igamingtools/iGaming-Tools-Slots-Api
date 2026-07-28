# Sweet Bonanza 1000

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/sweet-bonanza-1000-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sweet-bonanza-1000-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/sweet-bonanza-1000-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/sweet-bonanza-1000-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/sweet-bonanza-1000-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "sweet-bonanza-1000-b7",
  "name": "Sweet Bonanza 1000",
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
      "rtp": "96.50",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.52",
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
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Buy Super Free Spins",
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2024-06-03",
  "themes": [
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "sweets",
      "name": "Sweets"
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
      "page_url": "https://i-gaming.tools/slot-games/sweet-bonanza-1000-b7/"
    }
  },
  "series": {
    "slug": "sweet-bonanza",
    "name": "Sweet Bonanza"
  }
}
```

## Search Demand

`GET /api/v1/slots/sweet-bonanza-1000-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sweet-bonanza-1000-b7/demand/
```

**12-month volume (illustrative):** 560,680 · **trend:** declining · YoY -32.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 64,830 | growing |
| South Africa | 62,000 | growing |
| Philippines | 61,300 | flat |
| Turkey | 44,500 | growing |
| Greece | 36,760 | flat |
| Canada | 34,940 | growing |
| Switzerland | 16,890 | growing |
| Germany | 15,830 | declining |
| Netherlands | 13,550 | growing |
| United Kingdom | 12,700 | growing |

> Full per-country breakdown (80 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/sweet-bonanza-1000-b7/
- **Public page:** https://i-gaming.tools/slot-games/sweet-bonanza-1000-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
