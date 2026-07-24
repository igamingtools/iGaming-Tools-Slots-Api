# Tiny Toads

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/tiny-toads-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/tiny-toads-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/tiny-toads-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/tiny-toads-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/tiny-toads-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "tiny-toads-b7",
  "name": "Tiny Toads",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.51",
  "rtp_variants": [
    {
      "rtp": "96.51",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.45",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.46",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Random Toad Feature",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Buy Guaranteed Triple Toad Feature",
      "cost": "400.00",
      "is_default": false
    }
  ],
  "release_date": "2024-12-05",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
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
      "page_url": "https://i-gaming.tools/slot-games/tiny-toads-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/tiny-toads-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/tiny-toads-b7/demand/
```

**12-month volume (illustrative):** 3,290 · **trend:** declining · YoY -25.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 690 | declining |
| Canada | 160 | declining |
| Denmark | 140 | declining |
| United States | 140 | flat |
| El Salvador | 130 | flat |
| Indonesia | 130 | declining |
| Malaysia | 120 | declining |
| Mexico | 110 | declining |
| United Kingdom | 110 | declining |
| Greece | 100 | flat |

> Full per-country breakdown (44 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/tiny-toads-b7/
- **Public page:** https://i-gaming.tools/slot-games/tiny-toads-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
