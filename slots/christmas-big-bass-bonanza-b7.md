# Christmas Big Bass Bonanza

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/christmas-big-bass-bonanza-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/christmas-big-bass-bonanza-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/christmas-big-bass-bonanza-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/christmas-big-bass-bonanza-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/christmas-big-bass-bonanza-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "christmas-big-bass-bonanza-b7",
  "name": "Christmas Big Bass Bonanza",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.71",
  "rtp_variants": [
    {
      "rtp": "96.71",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.71",
      "variant": "bonus_buy",
      "is_default": false
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
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2021-12-02",
  "themes": [
    {
      "slug": "christmas",
      "name": "Christmas"
    },
    {
      "slug": "fishing",
      "name": "Fishing"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/christmas-big-bass-bonanza-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  },
  "series": {
    "slug": "big-bass",
    "name": "Big Bass"
  }
}
```

## Search Demand

`GET /api/v1/slots/christmas-big-bass-bonanza-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/christmas-big-bass-bonanza-b7/demand/
```

**12-month volume (illustrative):** 6,850 · **trend:** declining · YoY -24.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 1,910 | declining |
| Germany | 760 | flat |
| Greece | 560 | flat |
| Brazil | 350 | flat |
| Netherlands | 260 | flat |
| United States | 260 | declining |
| Switzerland | 240 | flat |
| Turkey | 210 | growing |
| Canada | 200 | declining |
| India | 160 | growing |

> Full per-country breakdown (51 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/christmas-big-bass-bonanza-b7/
- **Public page:** https://i-gaming.tools/slot-games/christmas-big-bass-bonanza-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
