# Gem Elevator

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/gem-elevator-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gem-elevator-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/gem-elevator-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/gem-elevator-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/gem-elevator-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "gem-elevator-b7",
  "name": "Gem Elevator",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.53",
  "rtp_variants": [
    {
      "rtp": "96.53",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.58",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 6,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2024-08-29",
  "themes": [
    {
      "slug": "gems",
      "name": "Gems"
    },
    {
      "slug": "mining",
      "name": "Mining"
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
      "slug": "tumble",
      "name": "Tumble"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/gem-elevator-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/gem-elevator-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gem-elevator-b7/demand/
```

**12-month volume (illustrative):** 1,080 · **trend:** declining · YoY -60.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 120 | flat |
| Malaysia | 120 | flat |
| Brazil | 110 | flat |
| Croatia | 80 | flat |
| India | 60 | flat |
| Ukraine | 50 | flat |
| Canada | 40 | flat |
| Finland | 40 | flat |
| Germany | 40 | flat |
| Lithuania | 40 | declining |

> Full per-country breakdown (33 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/gem-elevator-b7/
- **Public page:** https://i-gaming.tools/slot-games/gem-elevator-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
