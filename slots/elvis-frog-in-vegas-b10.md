# Elvis Frog in Vegas

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/elvis-frog-in-vegas-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/elvis-frog-in-vegas-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/elvis-frog-in-vegas-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/elvis-frog-in-vegas-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/elvis-frog-in-vegas-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "elvis-frog-in-vegas-b10",
  "name": "Elvis Frog in Vegas",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "95.30",
  "rtp_variants": [
    {
      "rtp": "95.30",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "med_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2020-05-13",
  "themes": [
    {
      "slug": "americana",
      "name": "Americana"
    },
    {
      "slug": "casino",
      "name": "Casino"
    },
    {
      "slug": "music",
      "name": "Music"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "gamble",
      "name": "Gamble"
    },
    {
      "slug": "giant-symbol",
      "name": "Giant Symbol"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/elvis-frog-in-vegas-b10/"
    }
  },
  "series": {
    "slug": "elvis-frog",
    "name": "Elvis Frog"
  }
}
```

## Search Demand

`GET /api/v1/slots/elvis-frog-in-vegas-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/elvis-frog-in-vegas-b10/demand/
```

**12-month volume (illustrative):** 2,840 · **trend:** growing · YoY +45.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 340 | declining |
| New Zealand | 280 | declining |
| Australia | 250 | growing |
| Canada | 180 | flat |
| United States | 140 | flat |
| United Kingdom | 120 | flat |
| Belarus | 110 | flat |
| Germany | 100 | flat |
| Netherlands | 100 | flat |
| Ukraine | 100 | flat |

> Full per-country breakdown (46 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/elvis-frog-in-vegas-b10/
- **Public page:** https://i-gaming.tools/slot-games/elvis-frog-in-vegas-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
