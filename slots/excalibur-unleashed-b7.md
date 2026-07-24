# Excalibur Unleashed

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/excalibur-unleashed-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/excalibur-unleashed-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/excalibur-unleashed-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/excalibur-unleashed-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/excalibur-unleashed-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "excalibur-unleashed-b7",
  "name": "Excalibur Unleashed",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.05",
  "rtp_variants": [
    {
      "rtp": "96.05",
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
  "mechanic": "lines",
  "reels": 5,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "85.00",
      "is_default": true
    }
  ],
  "release_date": "2023-04-27",
  "themes": [
    {
      "slug": "fantasy",
      "name": "Fantasy"
    },
    {
      "slug": "medieval",
      "name": "Medieval"
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
      "page_url": "https://i-gaming.tools/slot-games/excalibur-unleashed-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/excalibur-unleashed-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/excalibur-unleashed-b7/demand/
```

**12-month volume (illustrative):** 1,800 · **trend:** flat · YoY +3.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 120 | flat |
| Canada | 120 | growing |
| Greece | 120 | flat |
| India | 100 | flat |
| Netherlands | 80 | flat |
| United Kingdom | 80 | flat |
| Germany | 70 | flat |
| Romania | 70 | declining |
| Argentina | 60 | flat |
| Finland | 60 | flat |

> Full per-country breakdown (44 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/excalibur-unleashed-b7/
- **Public page:** https://i-gaming.tools/slot-games/excalibur-unleashed-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
