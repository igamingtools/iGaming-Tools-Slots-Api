# Ancient Egypt

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/ancient-egypt-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/ancient-egypt-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/ancient-egypt-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/ancient-egypt-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/ancient-egypt-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "ancient-egypt-b7",
  "name": "Ancient Egypt",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.13",
  "rtp_variants": [
    {
      "rtp": "96.13",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2018-01-24",
  "themes": [
    {
      "slug": "egyptian",
      "name": "Egyptian"
    }
  ],
  "features": [
    {
      "slug": "expanding-symbols",
      "name": "Expanding Symbols"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "pick_bonus",
      "name": "Pick Bonus"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/ancient-egypt-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/ancient-egypt-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/ancient-egypt-b7/demand/
```

**12-month volume (illustrative):** 1,270 · **trend:** growing · YoY +14.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 120 | flat |
| Germany | 90 | growing |
| El Salvador | 80 | declining |
| Greece | 80 | flat |
| Malaysia | 80 | declining |
| Romania | 70 | declining |
| Canada | 60 | declining |
| Finland | 60 | growing |
| United States | 60 | growing |
| India | 40 | flat |

> Full per-country breakdown (39 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/ancient-egypt-b7/
- **Public page:** https://i-gaming.tools/slot-games/ancient-egypt-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
