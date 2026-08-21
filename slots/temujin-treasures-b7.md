# Temujin Treasures

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/temujin-treasures-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/temujin-treasures-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/temujin-treasures-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/temujin-treasures-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/temujin-treasures-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "temujin-treasures-b7",
  "name": "Temujin Treasures",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.55",
  "rtp_variants": [
    {
      "rtp": "96.55",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.49",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Wheel with Free Games Bonus",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2021-03-01",
  "themes": [
    {
      "slug": "asian",
      "name": "Asian"
    },
    {
      "slug": "treasure",
      "name": "Treasure"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "random-awards",
      "name": "Random Awards"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/temujin-treasures-b7/"
    }
  },
  "studio": {
    "slug": "wild-streak-gaming",
    "name": "Wild Streak Gaming"
  }
}
```

## Search Demand

`GET /api/v1/slots/temujin-treasures-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/temujin-treasures-b7/demand/
```

**12-month volume (illustrative):** 1,090 · **trend:** declining · YoY -40.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 300 | flat |
| South Africa | 200 | declining |
| United States | 120 | declining |
| Indonesia | 60 | flat |
| Canada | 40 | flat |
| Germany | 40 | flat |
| Greece | 30 | flat |
| Lithuania | 30 | declining |
| Romania | 30 | flat |
| Tunisia | 30 | flat |

> Full per-country breakdown (26 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/temujin-treasures-b7/
- **Public page:** https://i-gaming.tools/slot-games/temujin-treasures-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
