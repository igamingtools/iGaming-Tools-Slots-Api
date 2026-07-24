# Pandemic Rising

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/pandemic-rising-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/pandemic-rising-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/pandemic-rising-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/pandemic-rising-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/pandemic-rising-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "pandemic-rising-b7",
  "name": "Pandemic Rising",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.51",
  "rtp_variants": [
    {
      "rtp": "96.51",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.53",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.53",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins",
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2025-10-27",
  "themes": [
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "post-apocalyptic",
      "name": "Post-Apocalyptic"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
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
      "page_url": "https://i-gaming.tools/slot-games/pandemic-rising-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/pandemic-rising-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/pandemic-rising-b7/demand/
```

**12-month volume (illustrative):** 4,620 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 460 | flat |
| Brazil | 390 | flat |
| Canada | 180 | flat |
| Finland | 180 | flat |
| Switzerland | 180 | growing |
| Germany | 170 | flat |
| Indonesia | 160 | growing |
| Malaysia | 160 | declining |
| United Kingdom | 150 | flat |
| Denmark | 140 | flat |

> Full per-country breakdown (52 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/pandemic-rising-b7/
- **Public page:** https://i-gaming.tools/slot-games/pandemic-rising-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
