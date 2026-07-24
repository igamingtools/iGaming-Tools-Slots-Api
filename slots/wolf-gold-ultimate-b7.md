# Wolf Gold Ultimate

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wolf-gold-ultimate-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wolf-gold-ultimate-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wolf-gold-ultimate-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wolf-gold-ultimate-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wolf-gold-ultimate-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wolf-gold-ultimate-b7",
  "name": "Wolf Gold Ultimate",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.57",
  "rtp_variants": [
    {
      "rtp": "96.57",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.56",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Money Respin",
      "cost": "80.00",
      "is_default": true
    }
  ],
  "release_date": "2024-11-07",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "western",
      "name": "Western"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/wolf-gold-ultimate-b7/"
    }
  },
  "series": {
    "slug": "wolf-gold",
    "name": "Wolf Gold"
  }
}
```

## Search Demand

`GET /api/v1/slots/wolf-gold-ultimate-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wolf-gold-ultimate-b7/demand/
```

**12-month volume (illustrative):** 5,450 · **trend:** growing · YoY +16.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Indonesia | 970 | declining |
| Canada | 900 | declining |
| Greece | 290 | declining |
| Germany | 200 | declining |
| Netherlands | 160 | declining |
| United States | 160 | flat |
| Belgium | 140 | flat |
| Finland | 140 | declining |
| New Zealand | 140 | declining |
| Australia | 130 | declining |

> Full per-country breakdown (50 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wolf-gold-ultimate-b7/
- **Public page:** https://i-gaming.tools/slot-games/wolf-gold-ultimate-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
