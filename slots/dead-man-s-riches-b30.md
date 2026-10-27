# Dead Man's Riches

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/dead-man-s-riches-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/dead-man-s-riches-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/dead-man-s-riches-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/dead-man-s-riches-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/dead-man-s-riches-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "dead-man-s-riches-b30",
  "name": "Dead Man's Riches",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.75",
  "rtp_variants": [
    {
      "rtp": "96.75",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-05-01",
  "themes": [
    {
      "slug": "ghosts",
      "name": "Ghosts"
    },
    {
      "slug": "ocean",
      "name": "Ocean"
    },
    {
      "slug": "pirates",
      "name": "Pirates"
    }
  ],
  "features": [
    {
      "slug": "free-spins-choice",
      "name": "Free Spins Choice"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
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
      "page_url": "https://i-gaming.tools/slot-games/dead-man-s-riches-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/dead-man-s-riches-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/dead-man-s-riches-b30/demand/
```

**12-month volume (illustrative):** 920 · **trend:** growing · YoY +100.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 320 | growing |
| India | 140 | declining |
| Philippines | 100 | flat |
| Indonesia | 90 | flat |
| Pakistan | 80 | flat |
| Greece | 30 | declining |
| Mexico | 30 | flat |
| Canada | 20 | flat |
| Kazakhstan | 20 | declining |
| Tunisia | 20 | flat |

> Full per-country breakdown (17 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/dead-man-s-riches-b30/
- **Public page:** https://i-gaming.tools/slot-games/dead-man-s-riches-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
