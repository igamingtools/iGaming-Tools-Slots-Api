# Book of Monsters

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/book-of-monsters-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/book-of-monsters-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/book-of-monsters-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/book-of-monsters-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/book-of-monsters-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "book-of-monsters-b7",
  "name": "Book of Monsters",
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
      "rtp": "96.50",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": null,
  "rows": 7,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2025-03-27",
  "themes": [
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "monsters",
      "name": "Monsters"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
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
      "page_url": "https://i-gaming.tools/slot-games/book-of-monsters-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/book-of-monsters-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/book-of-monsters-b7/demand/
```

**12-month volume (illustrative):** 7,520 · **trend:** flat · YoY -2.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 1,660 | declining |
| Brazil | 730 | declining |
| Switzerland | 300 | declining |
| Netherlands | 240 | declining |
| United Kingdom | 230 | declining |
| Canada | 220 | flat |
| Malaysia | 220 | growing |
| United States | 220 | declining |
| Denmark | 210 | declining |
| Finland | 200 | declining |

> Full per-country breakdown (50 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/book-of-monsters-b7/
- **Public page:** https://i-gaming.tools/slot-games/book-of-monsters-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
