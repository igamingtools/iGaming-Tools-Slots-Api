# Book of the Fallen

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/book-of-the-fallen-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/book-of-the-fallen-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/book-of-the-fallen-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/book-of-the-fallen-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/book-of-the-fallen-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "book-of-the-fallen-b7",
  "name": "Book of the Fallen",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.49",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.48",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2021-11-25",
  "themes": [
    {
      "slug": "adventure",
      "name": "Adventure"
    },
    {
      "slug": "egyptian",
      "name": "Egyptian"
    },
    {
      "slug": "treasure",
      "name": "Treasure"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "expanding-symbols",
      "name": "Expanding Symbols"
    },
    {
      "slug": "free-spins-choice",
      "name": "Free Spins Choice"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/book-of-the-fallen-b7/"
    }
  },
  "series": {
    "slug": "john-hunter",
    "name": "John Hunter"
  }
}
```

## Search Demand

`GET /api/v1/slots/book-of-the-fallen-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/book-of-the-fallen-b7/demand/
```

**12-month volume (illustrative):** 14,700 · **trend:** growing · YoY +13.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 5,340 | declining |
| Germany | 2,110 | growing |
| Switzerland | 930 | flat |
| Austria | 900 | flat |
| Italy | 530 | declining |
| Luxembourg | 260 | flat |
| United Kingdom | 250 | growing |
| Finland | 220 | flat |
| France | 220 | flat |
| Belgium | 180 | declining |

> Full per-country breakdown (55 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/book-of-the-fallen-b7/
- **Public page:** https://i-gaming.tools/slot-games/book-of-the-fallen-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
