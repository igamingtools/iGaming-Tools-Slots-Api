# Vampires vs Wolves

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/vampires-vs-wolves-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/vampires-vs-wolves-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/vampires-vs-wolves-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/vampires-vs-wolves-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/vampires-vs-wolves-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "vampires-vs-wolves-b7",
  "name": "Vampires vs Wolves",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.49",
  "rtp_variants": [
    {
      "rtp": "96.49",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.38",
      "variant": "default",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2019-08-22",
  "themes": [
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "vampires",
      "name": "Vampires"
    },
    {
      "slug": "werewolves",
      "name": "Werewolves"
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
      "slug": "stacked-symbols",
      "name": "Stacked Symbols"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/vampires-vs-wolves-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/vampires-vs-wolves-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/vampires-vs-wolves-b7/demand/
```

**12-month volume (illustrative):** 760 · **trend:** growing · YoY +28.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 100 | growing |
| Argentina | 80 | flat |
| Bulgaria | 60 | declining |
| Philippines | 50 | flat |
| Romania | 50 | flat |
| Finland | 40 | flat |
| Germany | 40 | flat |
| Mexico | 30 | flat |
| Portugal | 30 | flat |
| United Kingdom | 30 | flat |

> Full per-country breakdown (28 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/vampires-vs-wolves-b7/
- **Public page:** https://i-gaming.tools/slot-games/vampires-vs-wolves-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
