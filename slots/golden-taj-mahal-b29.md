# Golden Taj Mahal

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/golden-taj-mahal-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/golden-taj-mahal-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/golden-taj-mahal-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/golden-taj-mahal-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/golden-taj-mahal-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "golden-taj-mahal-b29",
  "name": "Golden Taj Mahal",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 6,
  "rows": 3,
  "jackpot_type": "progressive",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-04-16",
  "themes": [
    {
      "slug": "indian",
      "name": "Indian"
    },
    {
      "slug": "romance",
      "name": "Romance"
    },
    {
      "slug": "royalty",
      "name": "Royalty"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    },
    {
      "slug": "modifier-reel",
      "name": "Modifier Reel"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/golden-taj-mahal-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/golden-taj-mahal-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/golden-taj-mahal-b29/demand/
```

**12-month volume (illustrative):** 700 · **trend:** declining · YoY -52.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 490 | flat |
| India | 60 | flat |
| Lithuania | 60 | flat |
| Panama | 20 | flat |
| Poland | 20 | flat |
| Bulgaria | 10 | flat |
| Colombia | 10 | flat |
| Germany | 10 | flat |
| Italy | 10 | flat |
| Latvia | 10 | flat |

> Full per-country breakdown (10 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/golden-taj-mahal-b29/
- **Public page:** https://i-gaming.tools/slot-games/golden-taj-mahal-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
