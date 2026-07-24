# Fat Panda

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fat-panda-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fat-panda-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fat-panda-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fat-panda-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fat-panda-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fat-panda-b7",
  "name": "Fat Panda",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.07",
  "rtp_variants": [
    {
      "rtp": "96.07",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.07",
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
      "label": "Standard Free Spins",
      "cost": "70.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins",
      "cost": "300.00",
      "is_default": false
    }
  ],
  "release_date": "2023-06-15",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "money",
      "name": "Money"
    },
    {
      "slug": "panda",
      "name": "Panda"
    }
  ],
  "features": [
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "modifier-reel",
      "name": "Modifier Reel"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/fat-panda-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fat-panda-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fat-panda-b7/demand/
```

**12-month volume (illustrative):** 4,210 · **trend:** declining · YoY -8.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Indonesia | 710 | growing |
| Brazil | 370 | declining |
| Malaysia | 280 | flat |
| Canada | 200 | declining |
| Finland | 140 | growing |
| Greece | 130 | flat |
| Peru | 130 | flat |
| Switzerland | 120 | flat |
| United States | 120 | flat |
| Germany | 110 | flat |

> Full per-country breakdown (50 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fat-panda-b7/
- **Public page:** https://i-gaming.tools/slot-games/fat-panda-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
