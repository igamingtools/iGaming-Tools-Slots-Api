# Knockout Football Rush

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/knockout-football-rush-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/knockout-football-rush-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/knockout-football-rush-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/knockout-football-rush-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/knockout-football-rush-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "knockout-football-rush-b29",
  "name": "Knockout Football Rush",
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
  "reels": 3,
  "rows": 3,
  "jackpot_type": "progressive",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2020-03-31",
  "themes": [
    {
      "slug": "sports",
      "name": "Sports"
    }
  ],
  "features": [
    {
      "slug": "sticky_wild",
      "name": "Sticky Wild"
    },
    {
      "slug": "walking_wild",
      "name": "Walking Wild"
    },
    {
      "slug": "wild-multiplier",
      "name": "Wild Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/knockout-football-rush-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/knockout-football-rush-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/knockout-football-rush-b29/demand/
```

**12-month volume (illustrative):** 540 · **trend:** declining · YoY -51.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 220 | growing |
| Brazil | 90 | declining |
| India | 80 | flat |
| Kenya | 30 | flat |
| Peru | 20 | flat |
| United States | 20 | growing |
| Argentina | 10 | flat |
| Australia | 10 | flat |
| Italy | 10 | flat |
| Malta | 10 | flat |

> Full per-country breakdown (14 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/knockout-football-rush-b29/
- **Public page:** https://i-gaming.tools/slot-games/knockout-football-rush-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
