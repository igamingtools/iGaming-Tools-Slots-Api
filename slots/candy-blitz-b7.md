# Candy Blitz

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/candy-blitz-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/candy-blitz-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/candy-blitz-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/candy-blitz-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/candy-blitz-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "candy-blitz-b7",
  "name": "Candy Blitz",
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
    },
    {
      "rtp": "96.02",
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
    }
  ],
  "release_date": "2023-08-31",
  "themes": [
    {
      "slug": "sweets",
      "name": "Sweets"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "modifier-reel",
      "name": "Modifier Reel"
    },
    {
      "slug": "retrigger",
      "name": "Retrigger"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/candy-blitz-b7/"
    }
  },
  "series": {
    "slug": "candy-blitz",
    "name": "Candy Blitz"
  }
}
```

## Search Demand

`GET /api/v1/slots/candy-blitz-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/candy-blitz-b7/demand/
```

**12-month volume (illustrative):** 11,850 · **trend:** declining · YoY -15.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 2,330 | declining |
| Philippines | 1,220 | declining |
| South Africa | 880 | declining |
| Greece | 700 | flat |
| Argentina | 410 | growing |
| Canada | 400 | flat |
| Indonesia | 400 | declining |
| Peru | 280 | growing |
| Switzerland | 270 | growing |
| Turkey | 260 | flat |

> Full per-country breakdown (66 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/candy-blitz-b7/
- **Public page:** https://i-gaming.tools/slot-games/candy-blitz-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
