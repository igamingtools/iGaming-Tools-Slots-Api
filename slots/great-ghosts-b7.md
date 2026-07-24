# Great Ghosts\!

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/great-ghosts-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/great-ghosts-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/great-ghosts-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/great-ghosts-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/great-ghosts-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "great-ghosts-b7",
  "name": "Great Ghosts!",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Triple Ghost Respins",
      "cost": "300.00",
      "is_default": true
    }
  ],
  "release_date": "2026-04-23",
  "themes": [
    {
      "slug": "ghosts",
      "name": "Ghosts"
    },
    {
      "slug": "victorian",
      "name": "Victorian"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "growing-reels",
      "name": "Growing Reels"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/great-ghosts-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/great-ghosts-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/great-ghosts-b7/demand/
```

**12-month volume (illustrative):** 2,660 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 550 | declining |
| Greece | 270 | declining |
| Argentina | 140 | declining |
| Switzerland | 120 | declining |
| Canada | 100 | declining |
| Indonesia | 100 | declining |
| Malaysia | 100 | declining |
| Finland | 60 | flat |
| New Zealand | 60 | declining |
| Peru | 50 | flat |

> Full per-country breakdown (53 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/great-ghosts-b7/
- **Public page:** https://i-gaming.tools/slot-games/great-ghosts-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
