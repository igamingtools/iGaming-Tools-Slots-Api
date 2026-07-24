# Congo Cash

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/congo-cash-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/congo-cash-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/congo-cash-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/congo-cash-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/congo-cash-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "congo-cash-b7",
  "name": "Congo Cash",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.51",
  "rtp_variants": [
    {
      "rtp": "96.51",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2021-01-01",
  "themes": [
    {
      "slug": "africa",
      "name": "Africa"
    },
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "gems",
      "name": "Gems"
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
      "page_url": "https://i-gaming.tools/slot-games/congo-cash-b7/"
    }
  },
  "series": {
    "slug": "congo-cash",
    "name": "Congo Cash"
  }
}
```

## Search Demand

`GET /api/v1/slots/congo-cash-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/congo-cash-b7/demand/
```

**12-month volume (illustrative):** 4,980 · **trend:** flat · YoY +1.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Netherlands | 960 | declining |
| Argentina | 810 | flat |
| United Kingdom | 430 | declining |
| Indonesia | 280 | declining |
| Canada | 220 | flat |
| Brazil | 210 | flat |
| Ireland | 150 | flat |
| Switzerland | 150 | growing |
| India | 140 | flat |
| Germany | 120 | flat |

> Full per-country breakdown (45 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/congo-cash-b7/
- **Public page:** https://i-gaming.tools/slot-games/congo-cash-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
