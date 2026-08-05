# Doomsday Saloon

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/doomsday-saloon-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/doomsday-saloon-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/doomsday-saloon-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/doomsday-saloon-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/doomsday-saloon-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "doomsday-saloon-b10",
  "name": "Doomsday Saloon",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "97.00",
  "rtp_variants": [
    {
      "rtp": "97.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.00",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "97.00",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "cluster",
  "reels": 6,
  "rows": 8,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Regular",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "1 Wild Guaranteed",
      "cost": "200.00",
      "is_default": false
    }
  ],
  "release_date": "2025-04-29",
  "themes": [
    {
      "slug": "post-apocalyptic",
      "name": "Post-Apocalyptic"
    },
    {
      "slug": "pub",
      "name": "Pub"
    },
    {
      "slug": "western",
      "name": "Western"
    }
  ],
  "features": [
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier-spots",
      "name": "Multiplier Spots"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/doomsday-saloon-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/doomsday-saloon-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/doomsday-saloon-b10/demand/
```

**12-month volume (illustrative):** 850 · **trend:** growing · YoY +107.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 130 | flat |
| United States | 120 | flat |
| Greece | 110 | declining |
| United Kingdom | 90 | growing |
| Canada | 60 | flat |
| New Zealand | 50 | flat |
| Australia | 40 | flat |
| Finland | 40 | flat |
| Sweden | 40 | declining |
| Austria | 30 | flat |

> Full per-country breakdown (18 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/doomsday-saloon-b10/
- **Public page:** https://i-gaming.tools/slot-games/doomsday-saloon-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
