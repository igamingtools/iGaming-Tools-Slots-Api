# Gemhalla

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/gemhalla-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gemhalla-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/gemhalla-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/gemhalla-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/gemhalla-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "gemhalla-b10",
  "name": "Gemhalla",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "97.17",
  "rtp_variants": [
    {
      "rtp": "97.17",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "scatter_pays",
  "reels": 6,
  "rows": 5,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [],
  "release_date": "2023-06-15",
  "themes": [
    {
      "slug": "gems",
      "name": "Gems"
    },
    {
      "slug": "mythology",
      "name": "Mythology"
    },
    {
      "slug": "norse",
      "name": "Norse"
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
      "page_url": "https://i-gaming.tools/slot-games/gemhalla-b10/"
    }
  },
  "series": {
    "slug": "gemhalla",
    "name": "Gemhalla"
  }
}
```

## Search Demand

`GET /api/v1/slots/gemhalla-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gemhalla-b10/demand/
```

**12-month volume (illustrative):** 4,330 · **trend:** growing · YoY +19.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 360 | declining |
| Australia | 340 | declining |
| Switzerland | 240 | flat |
| United States | 240 | flat |
| Canada | 220 | flat |
| Finland | 220 | growing |
| United Arab Emirates | 200 | declining |
| Netherlands | 170 | flat |
| Turkey | 170 | flat |
| Belgium | 160 | declining |

> Full per-country breakdown (54 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/gemhalla-b10/
- **Public page:** https://i-gaming.tools/slot-games/gemhalla-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
