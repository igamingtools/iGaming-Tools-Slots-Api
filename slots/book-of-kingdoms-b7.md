# Book of Kingdoms

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/book-of-kingdoms-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/book-of-kingdoms-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/book-of-kingdoms-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/book-of-kingdoms-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/book-of-kingdoms-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "book-of-kingdoms-b7",
  "name": "Book of Kingdoms",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.69",
  "rtp_variants": [
    {
      "rtp": "96.69",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2020-11-16",
  "themes": [
    {
      "slug": "adventure",
      "name": "Adventure"
    },
    {
      "slug": "arabian",
      "name": "Arabian"
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
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/book-of-kingdoms-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  }
}
```

## Search Demand

`GET /api/v1/slots/book-of-kingdoms-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/book-of-kingdoms-b7/demand/
```

**12-month volume (illustrative):** 1,170 · **trend:** declining · YoY -10.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Austria | 110 | flat |
| Brazil | 110 | declining |
| Italy | 110 | declining |
| Indonesia | 70 | declining |
| Lithuania | 70 | flat |
| Finland | 60 | flat |
| Germany | 60 | flat |
| Switzerland | 60 | flat |
| United Kingdom | 60 | declining |
| Greece | 50 | flat |

> Full per-country breakdown (31 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/book-of-kingdoms-b7/
- **Public page:** https://i-gaming.tools/slot-games/book-of-kingdoms-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
