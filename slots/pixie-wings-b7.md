# Pixie Wings

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/pixie-wings-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/pixie-wings-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/pixie-wings-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/pixie-wings-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/pixie-wings-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "pixie-wings-b7",
  "name": "Pixie Wings",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
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
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2017-07-28",
  "themes": [
    {
      "slug": "fantasy",
      "name": "Fantasy"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "mystery_symbol",
      "name": "Mystery Symbol"
    },
    {
      "slug": "pick_bonus",
      "name": "Pick Bonus"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/pixie-wings-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/pixie-wings-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/pixie-wings-b7/demand/
```

**12-month volume (illustrative):** 900 · **trend:** flat · YoY +3.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 180 | declining |
| Hungary | 170 | declining |
| Greece | 90 | flat |
| Germany | 70 | declining |
| Indonesia | 70 | declining |
| Finland | 60 | flat |
| United Kingdom | 40 | flat |
| Switzerland | 30 | flat |
| Australia | 20 | flat |
| Belgium | 20 | flat |

> Full per-country breakdown (22 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/pixie-wings-b7/
- **Public page:** https://i-gaming.tools/slot-games/pixie-wings-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
