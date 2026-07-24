# Barn Festival

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/barn-festival-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/barn-festival-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/barn-festival-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/barn-festival-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/barn-festival-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "barn-festival-b7",
  "name": "Barn Festival",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.45",
  "rtp_variants": [
    {
      "rtp": "96.45",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.45",
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
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2022-03-31",
  "themes": [
    {
      "slug": "farm",
      "name": "Farm"
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
      "page_url": "https://i-gaming.tools/slot-games/barn-festival-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/barn-festival-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/barn-festival-b7/demand/
```

**12-month volume (illustrative):** 7,570 · **trend:** declining · YoY -44.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 2,420 | declining |
| Philippines | 690 | declining |
| Malaysia | 480 | declining |
| Indonesia | 400 | flat |
| Turkey | 380 | declining |
| Thailand | 200 | flat |
| Canada | 160 | growing |
| Switzerland | 150 | flat |
| Finland | 140 | growing |
| United States | 140 | declining |

> Full per-country breakdown (52 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/barn-festival-b7/
- **Public page:** https://i-gaming.tools/slot-games/barn-festival-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
