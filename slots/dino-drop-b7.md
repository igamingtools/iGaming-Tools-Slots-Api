# Dino Drop

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/dino-drop-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/dino-drop-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/dino-drop-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/dino-drop-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/dino-drop-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "dino-drop-b7",
  "name": "Dino Drop",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.47",
  "rtp_variants": [
    {
      "rtp": "96.47",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-08-18",
  "themes": [
    {
      "slug": "dinosaurs",
      "name": "Dinosaurs"
    }
  ],
  "features": [
    {
      "slug": "respin",
      "name": "Respin"
    },
    {
      "slug": "sticky_wild",
      "name": "Sticky Wild"
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
      "page_url": "https://i-gaming.tools/slot-games/dino-drop-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/dino-drop-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/dino-drop-b7/demand/
```

**12-month volume (illustrative):** 3,100 · **trend:** growing · YoY +3775.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 760 | declining |
| Greece | 170 | flat |
| Canada | 160 | flat |
| South Africa | 150 | growing |
| Ukraine | 110 | flat |
| Indonesia | 100 | flat |
| United Kingdom | 100 | flat |
| Tunisia | 90 | growing |
| Germany | 70 | declining |
| Malaysia | 60 | flat |

> Full per-country breakdown (58 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/dino-drop-b7/
- **Public page:** https://i-gaming.tools/slot-games/dino-drop-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
