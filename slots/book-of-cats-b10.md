# Book of Cats

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/book-of-cats-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/book-of-cats-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/book-of-cats-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/book-of-cats-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/book-of-cats-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "book-of-cats-b10",
  "name": "Book of Cats",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.99",
  "rtp_variants": [
    {
      "rtp": "96.99",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.83",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 6,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [],
  "release_date": "2020-07-08",
  "themes": [
    {
      "slug": "cats",
      "name": "Cats"
    },
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
      "slug": "free-spins-choice",
      "name": "Free Spins Choice"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/book-of-cats-b10/"
    }
  },
  "series": {
    "slug": "book-of-cats",
    "name": "Book of Cats"
  }
}
```

## Search Demand

`GET /api/v1/slots/book-of-cats-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/book-of-cats-b10/demand/
```

**12-month volume (illustrative):** 2,430 · **trend:** growing · YoY +11.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 420 | declining |
| Canada | 380 | declining |
| Brazil | 150 | flat |
| Greece | 120 | flat |
| Australia | 110 | declining |
| United States | 100 | declining |
| Netherlands | 70 | flat |
| Poland | 70 | growing |
| Denmark | 60 | flat |
| Finland | 60 | growing |

> Full per-country breakdown (42 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/book-of-cats-b10/
- **Public page:** https://i-gaming.tools/slot-games/book-of-cats-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
