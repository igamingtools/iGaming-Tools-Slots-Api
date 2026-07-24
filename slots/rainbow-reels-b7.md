# Rainbow Reels

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/rainbow-reels-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rainbow-reels-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/rainbow-reels-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/rainbow-reels-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/rainbow-reels-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "rainbow-reels-b7",
  "name": "Rainbow Reels",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.07",
  "rtp_variants": [
    {
      "rtp": "96.07",
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
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2023-09-01",
  "themes": [
    {
      "slug": "irish",
      "name": "Irish"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "scatter",
      "name": "Scatter"
    },
    {
      "slug": "sticky_wild",
      "name": "Sticky Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/rainbow-reels-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/rainbow-reels-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rainbow-reels-b7/demand/
```

**12-month volume (illustrative):** 1,600 · **trend:** declining · YoY -10.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Austria | 200 | declining |
| Brazil | 150 | declining |
| Greece | 110 | declining |
| United States | 100 | flat |
| Philippines | 90 | declining |
| Canada | 80 | declining |
| United Kingdom | 80 | flat |
| Indonesia | 70 | flat |
| Romania | 50 | declining |
| India | 40 | declining |

> Full per-country breakdown (36 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/rainbow-reels-b7/
- **Public page:** https://i-gaming.tools/slot-games/rainbow-reels-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
