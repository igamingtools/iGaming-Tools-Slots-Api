# Book of Cats MEGAWAYS

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/book-of-cats-megaways-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/book-of-cats-megaways-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/book-of-cats-megaways-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/book-of-cats-megaways-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/book-of-cats-megaways-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "book-of-cats-megaways-b10",
  "name": "Book of Cats MEGAWAYS",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "97.07",
  "rtp_variants": [
    {
      "rtp": "97.07",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.07",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "97.07",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "megaways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [],
  "release_date": "2022-11-03",
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
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "expanding-symbols",
      "name": "Expanding Symbols"
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
      "page_url": "https://i-gaming.tools/slot-games/book-of-cats-megaways-b10/"
    }
  },
  "series": {
    "slug": "book-of-cats",
    "name": "Book of Cats"
  }
}
```

## Search Demand

`GET /api/v1/slots/book-of-cats-megaways-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/book-of-cats-megaways-b10/demand/
```

**12-month volume (illustrative):** 1,510 · **trend:** growing · YoY +8.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Austria | 190 | declining |
| Canada | 120 | growing |
| Germany | 120 | flat |
| Greece | 110 | declining |
| United Kingdom | 110 | growing |
| United States | 110 | flat |
| Australia | 70 | flat |
| Brazil | 60 | flat |
| Finland | 60 | flat |
| Switzerland | 60 | flat |

> Full per-country breakdown (33 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/book-of-cats-megaways-b10/
- **Public page:** https://i-gaming.tools/slot-games/book-of-cats-megaways-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
