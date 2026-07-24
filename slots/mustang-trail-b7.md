# Mustang Trail

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mustang-trail-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mustang-trail-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mustang-trail-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mustang-trail-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mustang-trail-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mustang-trail-b7",
  "name": "Mustang Trail",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.04",
  "rtp_variants": [
    {
      "rtp": "96.04",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.05",
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
      "label": "Buy Free Spins",
      "cost": "50.00",
      "is_default": true
    }
  ],
  "release_date": "2023-08-01",
  "themes": [
    {
      "slug": "horses",
      "name": "Horses"
    },
    {
      "slug": "native-american",
      "name": "Native American"
    },
    {
      "slug": "western",
      "name": "Western"
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
      "page_url": "https://i-gaming.tools/slot-games/mustang-trail-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/mustang-trail-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mustang-trail-b7/demand/
```

**12-month volume (illustrative):** 1,930 · **trend:** declining · YoY -17.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 240 | growing |
| Latvia | 150 | flat |
| Indonesia | 130 | declining |
| Argentina | 100 | flat |
| Philippines | 100 | growing |
| Greece | 90 | growing |
| Finland | 80 | declining |
| Malaysia | 80 | flat |
| Romania | 80 | flat |
| Cyprus | 70 | flat |

> Full per-country breakdown (38 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mustang-trail-b7/
- **Public page:** https://i-gaming.tools/slot-games/mustang-trail-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
