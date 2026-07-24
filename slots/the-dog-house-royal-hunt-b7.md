# The Dog House – Royal Hunt

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/the-dog-house-royal-hunt-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/the-dog-house-royal-hunt-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/the-dog-house-royal-hunt-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/the-dog-house-royal-hunt-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/the-dog-house-royal-hunt-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "the-dog-house-royal-hunt-b7",
  "name": "The Dog House – Royal Hunt",
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
      "rtp": "96.51",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.51",
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
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Royal Free Spins",
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2025-03-31",
  "themes": [
    {
      "slug": "dogs",
      "name": "Dogs"
    },
    {
      "slug": "hunting",
      "name": "Hunting"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "respin",
      "name": "Respin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/the-dog-house-royal-hunt-b7/"
    }
  },
  "series": {
    "slug": "the-dog-house",
    "name": "The Dog House"
  }
}
```

## Search Demand

`GET /api/v1/slots/the-dog-house-royal-hunt-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/the-dog-house-royal-hunt-b7/demand/
```

**12-month volume (illustrative):** 8,300 · **trend:** growing · YoY +59.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 1,180 | declining |
| Switzerland | 480 | flat |
| Ukraine | 470 | declining |
| Belarus | 320 | flat |
| Brazil | 320 | declining |
| Canada | 300 | flat |
| Finland | 240 | flat |
| Indonesia | 240 | flat |
| Malaysia | 220 | growing |
| Romania | 220 | declining |

> Full per-country breakdown (58 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/the-dog-house-royal-hunt-b7/
- **Public page:** https://i-gaming.tools/slot-games/the-dog-house-royal-hunt-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
