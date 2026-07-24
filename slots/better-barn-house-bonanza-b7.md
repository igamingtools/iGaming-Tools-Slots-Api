# Better Barn House Bonanza

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/better-barn-house-bonanza-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/better-barn-house-bonanza-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/better-barn-house-bonanza-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/better-barn-house-bonanza-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/better-barn-house-bonanza-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "better-barn-house-bonanza-b7",
  "name": "Better Barn House Bonanza",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "ways",
  "reels": 5,
  "rows": null,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Wheel Bonus",
      "cost": "50.00",
      "is_default": true
    },
    {
      "label": "Bigger Wheel Bonus",
      "cost": "150.00",
      "is_default": false
    }
  ],
  "release_date": "2026-06-22",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "farm",
      "name": "Farm"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
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
      "page_url": "https://i-gaming.tools/slot-games/better-barn-house-bonanza-b7/"
    }
  },
  "series": {
    "slug": "barn-house-bonanza",
    "name": "Barn House Bonanza"
  }
}
```

## Search Demand

`GET /api/v1/slots/better-barn-house-bonanza-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/better-barn-house-bonanza-b7/demand/
```

**12-month volume (illustrative):** 360 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Indonesia | 70 | growing |
| Belgium | 40 | growing |
| Canada | 20 | declining |
| India | 20 | growing |
| Malaysia | 20 | growing |
| Thailand | 20 | growing |
| Argentina | 10 | declining |
| Brazil | 10 | declining |
| Colombia | 10 | declining |
| El Salvador | 10 | growing |

> Full per-country breakdown (23 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/better-barn-house-bonanza-b7/
- **Public page:** https://i-gaming.tools/slot-games/better-barn-house-bonanza-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
