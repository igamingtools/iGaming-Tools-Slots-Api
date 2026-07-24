# Greek Gods

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/greek-gods-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/greek-gods-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/greek-gods-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/greek-gods-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/greek-gods-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "greek-gods-b7",
  "name": "Greek Gods",
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
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2019-12-12",
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
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "random-awards",
      "name": "Random Awards"
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
      "page_url": "https://i-gaming.tools/slot-games/greek-gods-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/greek-gods-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/greek-gods-b7/demand/
```

**12-month volume (illustrative):** 1,070 · **trend:** declining · YoY -9.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 140 | flat |
| Brazil | 120 | flat |
| Greece | 110 | flat |
| Indonesia | 100 | declining |
| Argentina | 90 | growing |
| Philippines | 70 | growing |
| Switzerland | 60 | flat |
| Canada | 40 | declining |
| United States | 40 | growing |
| Netherlands | 30 | flat |

> Full per-country breakdown (28 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/greek-gods-b7/
- **Public page:** https://i-gaming.tools/slot-games/greek-gods-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
