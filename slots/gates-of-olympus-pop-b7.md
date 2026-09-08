# Gates of Olympus POP

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/gates-of-olympus-pop-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gates-of-olympus-pop-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/gates-of-olympus-pop-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/gates-of-olympus-pop-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/gates-of-olympus-pop-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "gates-of-olympus-pop-b7",
  "name": "Gates of Olympus POP",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "97.05",
  "rtp_variants": [
    {
      "rtp": "97.05",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "low",
  "mechanic": "scatter_pays",
  "reels": 3,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-08-31",
  "themes": [
    {
      "slug": "ancient-greece",
      "name": "Ancient Greece"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/gates-of-olympus-pop-b7/"
    }
  },
  "series": {
    "slug": "gates-of-olympus",
    "name": "Gates of Olympus"
  }
}
```

## Search Demand

`GET /api/v1/slots/gates-of-olympus-pop-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gates-of-olympus-pop-b7/demand/
```

**12-month volume (illustrative):** 370 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Indonesia | 70 | growing |
| Philippines | 50 | growing |
| Malaysia | 40 | growing |
| Brazil | 20 | growing |
| United States | 20 | growing |
| Australia | 10 | growing |
| Bulgaria | 10 | growing |
| France | 10 | growing |
| Germany | 10 | growing |
| Greece | 10 | growing |

> Full per-country breakdown (22 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/gates-of-olympus-pop-b7/
- **Public page:** https://i-gaming.tools/slot-games/gates-of-olympus-pop-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
