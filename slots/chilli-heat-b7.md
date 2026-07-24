# Chilli Heat

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/chilli-heat-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chilli-heat-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/chilli-heat-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/chilli-heat-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/chilli-heat-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "chilli-heat-b7",
  "name": "Chilli Heat",
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
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2018-01-01",
  "themes": [
    {
      "slug": "food",
      "name": "Food"
    },
    {
      "slug": "mexican",
      "name": "Mexican"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
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
      "page_url": "https://i-gaming.tools/slot-games/chilli-heat-b7/"
    }
  },
  "series": {
    "slug": "chilli-heat",
    "name": "Chilli Heat"
  }
}
```

## Search Demand

`GET /api/v1/slots/chilli-heat-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chilli-heat-b7/demand/
```

**12-month volume (illustrative):** 6,090 · **trend:** declining · YoY -5.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 890 | declining |
| New Zealand | 510 | declining |
| Argentina | 360 | declining |
| Brazil | 340 | declining |
| Canada | 320 | declining |
| Mexico | 220 | declining |
| Lithuania | 190 | declining |
| Greece | 170 | declining |
| Sweden | 150 | declining |
| Portugal | 140 | declining |

> Full per-country breakdown (54 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/chilli-heat-b7/
- **Public page:** https://i-gaming.tools/slot-games/chilli-heat-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
