# Pompeii Megareels Megaways™

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/pompeii-megareels-megawaystm-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/pompeii-megareels-megawaystm-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/pompeii-megareels-megawaystm-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/pompeii-megareels-megawaystm-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/pompeii-megareels-megawaystm-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "pompeii-megareels-megawaystm-b7",
  "name": "Pompeii Megareels Megaways™",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.00",
  "rtp_variants": [
    {
      "rtp": "96.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.06",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.02",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "megaways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Buy Double Multiplier Free Spins",
      "cost": "300.00",
      "is_default": false
    }
  ],
  "release_date": "2024-02-15",
  "themes": [
    {
      "slug": "ancient-rome",
      "name": "Ancient Rome"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "megaways",
      "name": "Megaways"
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
      "page_url": "https://i-gaming.tools/slot-games/pompeii-megareels-megawaystm-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/pompeii-megareels-megawaystm-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/pompeii-megareels-megawaystm-b7/demand/
```

**12-month volume (illustrative):** 3,420 · **trend:** declining · YoY -16.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 420 | declining |
| Brazil | 280 | declining |
| Greece | 270 | declining |
| Switzerland | 180 | flat |
| Canada | 160 | declining |
| Malaysia | 140 | flat |
| Argentina | 120 | declining |
| Philippines | 120 | flat |
| United Kingdom | 120 | declining |
| Indonesia | 110 | flat |

> Full per-country breakdown (47 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/pompeii-megareels-megawaystm-b7/
- **Public page:** https://i-gaming.tools/slot-games/pompeii-megareels-megawaystm-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
