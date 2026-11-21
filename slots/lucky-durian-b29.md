# Lucky Durian

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/lucky-durian-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lucky-durian-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/lucky-durian-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/lucky-durian-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/lucky-durian-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "lucky-durian-b29",
  "name": "Lucky Durian",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.88",
  "rtp_variants": [
    {
      "rtp": "96.88",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "very_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "pooled",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2022-01-25",
  "themes": [
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "tropical",
      "name": "Tropical"
    }
  ],
  "features": [
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "respin",
      "name": "Respin"
    },
    {
      "slug": "sticky_wild",
      "name": "Sticky Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/lucky-durian-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/lucky-durian-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/lucky-durian-b29/demand/
```

**12-month volume (illustrative):** 6,630 · **trend:** declining · YoY -37.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 5,920 | declining |
| United States | 180 | flat |
| India | 120 | flat |
| Indonesia | 50 | flat |
| Lithuania | 50 | growing |
| Canada | 40 | growing |
| Malaysia | 40 | flat |
| Tunisia | 40 | flat |
| Italy | 20 | flat |
| Pakistan | 20 | flat |

> Full per-country breakdown (20 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/lucky-durian-b29/
- **Public page:** https://i-gaming.tools/slot-games/lucky-durian-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
