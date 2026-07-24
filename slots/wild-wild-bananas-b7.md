# Wild Wild Bananas

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wild-wild-bananas-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-wild-bananas-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wild-wild-bananas-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wild-wild-bananas-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wild-wild-bananas-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wild-wild-bananas-b7",
  "name": "Wild Wild Bananas",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.10",
  "rtp_variants": [
    {
      "rtp": "96.10",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.15",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 5,
  "rows": null,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2023-01-09",
  "themes": [
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "jungle",
      "name": "Jungle"
    },
    {
      "slug": "monkeys",
      "name": "Monkeys"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "growing-reels",
      "name": "Growing Reels"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/wild-wild-bananas-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/wild-wild-bananas-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-wild-bananas-b7/demand/
```

**12-month volume (illustrative):** 1,140 · **trend:** declining · YoY -20.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 200 | flat |
| Philippines | 110 | declining |
| Canada | 100 | growing |
| Greece | 80 | flat |
| Indonesia | 60 | flat |
| Italy | 50 | flat |
| United Kingdom | 50 | declining |
| Argentina | 40 | flat |
| Finland | 40 | flat |
| Romania | 40 | declining |

> Full per-country breakdown (33 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wild-wild-bananas-b7/
- **Public page:** https://i-gaming.tools/slot-games/wild-wild-bananas-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
