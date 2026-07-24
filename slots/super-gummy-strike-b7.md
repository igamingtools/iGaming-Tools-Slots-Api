# Super Gummy Strike

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/super-gummy-strike-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/super-gummy-strike-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/super-gummy-strike-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/super-gummy-strike-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/super-gummy-strike-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "super-gummy-strike-b7",
  "name": "Super Gummy Strike",
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
      "rtp": "96.48",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.48",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Respins",
      "cost": "200.00",
      "is_default": true
    },
    {
      "label": "Super Respins",
      "cost": "400.00",
      "is_default": false
    }
  ],
  "release_date": "2025-11-17",
  "themes": [
    {
      "slug": "classic",
      "name": "Classic"
    },
    {
      "slug": "food",
      "name": "Food"
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
      "slug": "wild",
      "name": "Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/super-gummy-strike-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/super-gummy-strike-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/super-gummy-strike-b7/demand/
```

**12-month volume (illustrative):** 5,340 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 1,330 | declining |
| Greece | 620 | declining |
| Canada | 220 | flat |
| Netherlands | 170 | declining |
| Peru | 170 | flat |
| Belgium | 160 | flat |
| Denmark | 160 | flat |
| Indonesia | 160 | flat |
| Malaysia | 140 | flat |
| Philippines | 120 | flat |

> Full per-country breakdown (55 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/super-gummy-strike-b7/
- **Public page:** https://i-gaming.tools/slot-games/super-gummy-strike-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
