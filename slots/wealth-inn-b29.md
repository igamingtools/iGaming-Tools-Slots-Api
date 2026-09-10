# Wealth Inn

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wealth-inn-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wealth-inn-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wealth-inn-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wealth-inn-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wealth-inn-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wealth-inn-b29",
  "name": "Wealth Inn",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.67",
  "rtp_variants": [
    {
      "rtp": "96.67",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "low",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "progressive",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2020-07-29",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "money",
      "name": "Money"
    }
  ],
  "features": [
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "wild",
      "name": "Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/wealth-inn-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/wealth-inn-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wealth-inn-b29/demand/
```

**12-month volume (illustrative):** 61,580 · **trend:** declining · YoY -29.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 59,000 | flat |
| United States | 520 | flat |
| India | 240 | flat |
| Canada | 220 | flat |
| United Kingdom | 140 | growing |
| New Zealand | 110 | flat |
| Indonesia | 100 | declining |
| Pakistan | 100 | flat |
| Philippines | 70 | flat |
| Tunisia | 70 | flat |

> Full per-country breakdown (52 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wealth-inn-b29/
- **Public page:** https://i-gaming.tools/slot-games/wealth-inn-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
