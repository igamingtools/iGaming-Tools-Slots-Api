# Chilli Heat Spicy Spins

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/chilli-heat-spicy-spins-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chilli-heat-spicy-spins-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/chilli-heat-spicy-spins-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/chilli-heat-spicy-spins-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/chilli-heat-spicy-spins-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "chilli-heat-spicy-spins-b7",
  "name": "Chilli Heat Spicy Spins",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.58",
  "rtp_variants": [
    {
      "rtp": "96.58",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.58",
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
      "label": "Buy Respins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2025-07-17",
  "themes": [
    {
      "slug": "mexican",
      "name": "Mexican"
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
      "page_url": "https://i-gaming.tools/slot-games/chilli-heat-spicy-spins-b7/"
    }
  },
  "series": {
    "slug": "chilli-heat",
    "name": "Chilli Heat"
  }
}
```

## Search Demand

`GET /api/v1/slots/chilli-heat-spicy-spins-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chilli-heat-spicy-spins-b7/demand/
```

**12-month volume (illustrative):** 3,430 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 330 | flat |
| Brazil | 260 | declining |
| Canada | 200 | declining |
| United Kingdom | 180 | flat |
| Indonesia | 140 | flat |
| Malaysia | 140 | growing |
| Argentina | 130 | flat |
| Portugal | 120 | flat |
| Switzerland | 120 | flat |
| Australia | 100 | flat |

> Full per-country breakdown (50 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/chilli-heat-spicy-spins-b7/
- **Public page:** https://i-gaming.tools/slot-games/chilli-heat-spicy-spins-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
