# Arctic Hunt

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/arctic-hunt-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/arctic-hunt-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/arctic-hunt-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/arctic-hunt-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/arctic-hunt-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "arctic-hunt-b29",
  "name": "Arctic Hunt",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.61",
  "rtp_variants": [
    {
      "rtp": "96.61",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "very_high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "pooled",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-05-14",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "forest",
      "name": "Forest"
    },
    {
      "slug": "winter",
      "name": "Winter"
    }
  ],
  "features": [
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "retrigger",
      "name": "Retrigger"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/arctic-hunt-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/arctic-hunt-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/arctic-hunt-b29/demand/
```

**12-month volume (illustrative):** 340 · **trend:** declining · YoY -46.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 200 | flat |
| India | 40 | flat |
| Romania | 30 | growing |
| Tunisia | 20 | growing |
| Argentina | 10 | flat |
| Brazil | 10 | growing |
| Latvia | 10 | flat |
| Lithuania | 10 | flat |
| Philippines | 10 | flat |

> Full per-country breakdown (9 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/arctic-hunt-b29/
- **Public page:** https://i-gaming.tools/slot-games/arctic-hunt-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
