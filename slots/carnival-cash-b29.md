# Carnival Cash

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/carnival-cash-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/carnival-cash-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/carnival-cash-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/carnival-cash-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/carnival-cash-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "carnival-cash-b29",
  "name": "Carnival Cash",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "95.97",
  "rtp_variants": [
    {
      "rtp": "95.97",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "very_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "progressive",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": null,
  "themes": [
    {
      "slug": "carnival",
      "name": "Carnival"
    }
  ],
  "features": [
    {
      "slug": "scatter",
      "name": "Scatter"
    },
    {
      "slug": "super-spin",
      "name": "Super Spin"
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
      "page_url": "https://i-gaming.tools/slot-games/carnival-cash-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/carnival-cash-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/carnival-cash-b29/demand/
```

**12-month volume (illustrative):** 240 · **trend:** declining · YoY -22.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 170 | flat |
| India | 60 | flat |
| Greece | 10 | flat |

> Full per-country breakdown (3 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/carnival-cash-b29/
- **Public page:** https://i-gaming.tools/slot-games/carnival-cash-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
