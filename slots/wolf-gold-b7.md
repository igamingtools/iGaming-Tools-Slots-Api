# Wolf Gold

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wolf-gold-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wolf-gold-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wolf-gold-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wolf-gold-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wolf-gold-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wolf-gold-b7",
  "name": "Wolf Gold",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.00",
  "rtp_variants": [
    {
      "rtp": "96.00",
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
  "release_date": "2017-04-27",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "western",
      "name": "Western"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "giant-symbol",
      "name": "Giant Symbol"
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
      "page_url": "https://i-gaming.tools/slot-games/wolf-gold-b7/"
    }
  },
  "series": {
    "slug": "wolf-gold",
    "name": "Wolf Gold"
  }
}
```

## Search Demand

`GET /api/v1/slots/wolf-gold-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wolf-gold-b7/demand/
```

**12-month volume (illustrative):** 12,660 · **trend:** declining · YoY -15.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 1,960 | declining |
| Germany | 1,250 | declining |
| Netherlands | 1,040 | declining |
| United Kingdom | 970 | declining |
| Canada | 840 | declining |
| Australia | 420 | declining |
| United States | 370 | declining |
| Ukraine | 340 | declining |
| Switzerland | 330 | declining |
| Spain | 300 | declining |

> Full per-country breakdown (58 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wolf-gold-b7/
- **Public page:** https://i-gaming.tools/slot-games/wolf-gold-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
