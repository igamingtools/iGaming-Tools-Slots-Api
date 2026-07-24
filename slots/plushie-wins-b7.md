# Plushie Wins

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/plushie-wins-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/plushie-wins-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/plushie-wins-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/plushie-wins-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/plushie-wins-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "plushie-wins-b7",
  "name": "Plushie Wins",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.84",
  "rtp_variants": [
    {
      "rtp": "96.84",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "low",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-06-16",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "carnival",
      "name": "Carnival"
    }
  ],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/plushie-wins-b7/"
    }
  },
  "studio": {
    "slug": "fat-panda",
    "name": "FAT PANDA"
  }
}
```

## Search Demand

`GET /api/v1/slots/plushie-wins-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/plushie-wins-b7/demand/
```

**12-month volume (illustrative):** 1,110 · **trend:** growing · YoY +40.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 390 | flat |
| Greece | 100 | growing |
| Canada | 60 | flat |
| Argentina | 50 | flat |
| Lithuania | 50 | growing |
| Peru | 40 | flat |
| Spain | 40 | declining |
| Indonesia | 30 | flat |
| Mexico | 30 | flat |
| Thailand | 30 | flat |

> Full per-country breakdown (30 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/plushie-wins-b7/
- **Public page:** https://i-gaming.tools/slot-games/plushie-wins-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
