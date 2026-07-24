# Moleionaire

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/moleionaire-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/moleionaire-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/moleionaire-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/moleionaire-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/moleionaire-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "moleionaire-b7",
  "name": "Moleionaire",
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
      "rtp": "96.08",
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
      "cost": "90.00",
      "is_default": true
    }
  ],
  "release_date": "2024-11-04",
  "themes": [
    {
      "slug": "food",
      "name": "Food"
    },
    {
      "slug": "money",
      "name": "Money"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "random-wilds",
      "name": "Random Wilds"
    },
    {
      "slug": "scatter",
      "name": "Scatter"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/moleionaire-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/moleionaire-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/moleionaire-b7/demand/
```

**12-month volume (illustrative):** 1,110 · **trend:** declining · YoY -21.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 120 | flat |
| Finland | 120 | declining |
| Philippines | 80 | growing |
| Bulgaria | 70 | declining |
| Malaysia | 60 | flat |
| Netherlands | 60 | growing |
| Portugal | 60 | flat |
| Greece | 50 | flat |
| Romania | 50 | flat |
| Indonesia | 40 | growing |

> Full per-country breakdown (32 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/moleionaire-b7/
- **Public page:** https://i-gaming.tools/slot-games/moleionaire-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
