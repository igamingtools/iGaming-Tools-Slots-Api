# Ninja vs Samurai

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/ninja-vs-samurai-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/ninja-vs-samurai-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/ninja-vs-samurai-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/ninja-vs-samurai-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/ninja-vs-samurai-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "ninja-vs-samurai-b30",
  "name": "Ninja vs Samurai",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "97.44",
  "rtp_variants": [
    {
      "rtp": "97.44",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2019-10-01",
  "themes": [
    {
      "slug": "japanese",
      "name": "Japanese"
    },
    {
      "slug": "martial-arts",
      "name": "Martial Arts"
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
      "slug": "stacked-wild",
      "name": "Stacked Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/ninja-vs-samurai-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/ninja-vs-samurai-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/ninja-vs-samurai-b30/demand/
```

**12-month volume (illustrative):** 1,430 · **trend:** declining · YoY -12.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 370 | declining |
| Pakistan | 180 | flat |
| India | 160 | flat |
| Philippines | 160 | flat |
| Indonesia | 120 | flat |
| United States | 80 | flat |
| Thailand | 50 | growing |
| Tunisia | 40 | flat |
| Canada | 20 | flat |
| Greece | 20 | flat |

> Full per-country breakdown (26 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/ninja-vs-samurai-b30/
- **Public page:** https://i-gaming.tools/slot-games/ninja-vs-samurai-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
