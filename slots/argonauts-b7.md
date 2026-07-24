# Argonauts

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/argonauts-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/argonauts-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/argonauts-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/argonauts-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/argonauts-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "argonauts-b7",
  "name": "Argonauts",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.47",
  "rtp_variants": [
    {
      "rtp": "96.47",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.46",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Respins",
      "cost": "60.00",
      "is_default": true
    }
  ],
  "release_date": "2025-08-07",
  "themes": [
    {
      "slug": "ancient-greece",
      "name": "Ancient Greece"
    },
    {
      "slug": "mythology",
      "name": "Mythology"
    }
  ],
  "features": [
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
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
      "page_url": "https://i-gaming.tools/slot-games/argonauts-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/argonauts-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/argonauts-b7/demand/
```

**12-month volume (illustrative):** 2,560 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 430 | flat |
| Brazil | 270 | declining |
| Switzerland | 150 | growing |
| Spain | 110 | flat |
| Peru | 90 | flat |
| Finland | 80 | flat |
| Indonesia | 80 | growing |
| Romania | 80 | growing |
| Italy | 70 | flat |
| Netherlands | 70 | flat |

> Full per-country breakdown (50 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/argonauts-b7/
- **Public page:** https://i-gaming.tools/slot-games/argonauts-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
