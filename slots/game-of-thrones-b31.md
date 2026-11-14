# Game of Thrones

**Provider:** Blueprint Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/game-of-thrones-b31/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/game-of-thrones-b31/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/game-of-thrones-b31/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/game-of-thrones-b31/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/game-of-thrones-b31/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "game-of-thrones-b31",
  "name": "Game of Thrones",
  "status": "active",
  "provider": {
    "slug": "blueprint-gaming",
    "name": "Blueprint Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "94.00",
  "rtp_variants": [
    {
      "rtp": "94.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "90.00",
      "variant": "operator_config",
      "is_default": false
    },
    {
      "rtp": "92.00",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "med_high",
  "mechanic": "ways",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-03-26",
  "themes": [
    {
      "slug": "dragons",
      "name": "Dragons"
    },
    {
      "slug": "fantasy",
      "name": "Fantasy"
    },
    {
      "slug": "medieval",
      "name": "Medieval"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
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
      "page_url": "https://i-gaming.tools/slot-games/game-of-thrones-b31/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/game-of-thrones-b31/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/game-of-thrones-b31/demand/
```

**12-month volume (illustrative):** 21,190 · **trend:** flat · YoY -4.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 9,840 | flat |
| Germany | 6,560 | growing |
| South Africa | 940 | declining |
| United Kingdom | 500 | declining |
| Austria | 410 | growing |
| Portugal | 390 | growing |
| United States | 300 | declining |
| India | 200 | flat |
| Canada | 140 | flat |
| Switzerland | 140 | declining |

> Full per-country breakdown (60 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/game-of-thrones-b31/
- **Public page:** https://i-gaming.tools/slot-games/game-of-thrones-b31/
- **Full schema:** https://i-gaming.tools/api/docs/
