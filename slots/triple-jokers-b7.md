# Triple Jokers

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/triple-jokers-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/triple-jokers-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/triple-jokers-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/triple-jokers-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/triple-jokers-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "triple-jokers-b7",
  "name": "Triple Jokers",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.47",
  "rtp_variants": [
    {
      "rtp": "96.47",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2019-06-05",
  "themes": [
    {
      "slug": "joker",
      "name": "Joker"
    }
  ],
  "features": [
    {
      "slug": "respin",
      "name": "Respin"
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
      "page_url": "https://i-gaming.tools/slot-games/triple-jokers-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/triple-jokers-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/triple-jokers-b7/demand/
```

**12-month volume (illustrative):** 960 · **trend:** declining · YoY -20.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Argentina | 110 | declining |
| Lithuania | 70 | declining |
| Canada | 60 | flat |
| El Salvador | 60 | declining |
| Mexico | 60 | flat |
| United States | 60 | flat |
| Greece | 50 | flat |
| Netherlands | 50 | flat |
| Brazil | 40 | flat |
| Czech Republic | 40 | flat |

> Full per-country breakdown (34 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/triple-jokers-b7/
- **Public page:** https://i-gaming.tools/slot-games/triple-jokers-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
