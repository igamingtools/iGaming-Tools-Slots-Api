# Gold Train

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/gold-train-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gold-train-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/gold-train-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/gold-train-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/gold-train-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "gold-train-b7",
  "name": "Gold Train",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "97.16",
  "rtp_variants": [
    {
      "rtp": "97.16",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2017-06-01",
  "themes": [
    {
      "slug": "classic",
      "name": "Classic"
    },
    {
      "slug": "trains",
      "name": "Trains"
    },
    {
      "slug": "western",
      "name": "Western"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "retrigger",
      "name": "Retrigger"
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
      "page_url": "https://i-gaming.tools/slot-games/gold-train-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/gold-train-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gold-train-b7/demand/
```

**12-month volume (illustrative):** 1,940 · **trend:** flat · YoY -1.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 200 | flat |
| Brazil | 140 | flat |
| Philippines | 120 | flat |
| United Kingdom | 100 | declining |
| Greece | 90 | growing |
| Switzerland | 90 | flat |
| Finland | 80 | flat |
| Mexico | 80 | declining |
| Netherlands | 80 | declining |
| Romania | 70 | flat |

> Full per-country breakdown (41 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/gold-train-b7/
- **Public page:** https://i-gaming.tools/slot-games/gold-train-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
