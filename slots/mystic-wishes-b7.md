# Mystic Wishes

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mystic-wishes-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mystic-wishes-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mystic-wishes-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mystic-wishes-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mystic-wishes-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mystic-wishes-b7",
  "name": "Mystic Wishes",
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
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-10-27",
  "themes": [
    {
      "slug": "arabian",
      "name": "Arabian"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "respin",
      "name": "Respin"
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
      "page_url": "https://i-gaming.tools/slot-games/mystic-wishes-b7/"
    }
  },
  "studio": {
    "slug": "fat-panda",
    "name": "FAT PANDA"
  }
}
```

## Search Demand

`GET /api/v1/slots/mystic-wishes-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mystic-wishes-b7/demand/
```

**12-month volume (illustrative):** 1,630 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 340 | flat |
| Greece | 160 | growing |
| Indonesia | 60 | flat |
| Switzerland | 60 | flat |
| United Kingdom | 60 | growing |
| Latvia | 50 | flat |
| Australia | 40 | declining |
| Canada | 40 | flat |
| Cyprus | 40 | flat |
| Germany | 40 | growing |

> Full per-country breakdown (43 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mystic-wishes-b7/
- **Public page:** https://i-gaming.tools/slot-games/mystic-wishes-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
