# Magic Journey

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/magic-journey-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/magic-journey-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/magic-journey-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/magic-journey-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/magic-journey-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "magic-journey-b7",
  "name": "Magic Journey",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.54",
  "rtp_variants": [
    {
      "rtp": "96.54",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2020-01-01",
  "themes": [
    {
      "slug": "adventure",
      "name": "Adventure"
    },
    {
      "slug": "chinese",
      "name": "Chinese"
    }
  ],
  "features": [
    {
      "slug": "respin",
      "name": "Respin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/magic-journey-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/magic-journey-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/magic-journey-b7/demand/
```

**12-month volume (illustrative):** 490 · **trend:** growing · YoY +48.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 140 | flat |
| Philippines | 60 | flat |
| Indonesia | 50 | flat |
| Finland | 40 | flat |
| Argentina | 30 | flat |
| Germany | 20 | flat |
| Malaysia | 20 | flat |
| United Kingdom | 20 | flat |
| United States | 20 | flat |
| Chile | 10 | flat |

> Full per-country breakdown (18 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/magic-journey-b7/
- **Public page:** https://i-gaming.tools/slot-games/magic-journey-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
