# Zombie Carnival

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/zombie-carnival-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/zombie-carnival-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/zombie-carnival-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/zombie-carnival-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/zombie-carnival-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "zombie-carnival-b7",
  "name": "Zombie Carnival",
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
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "80.00",
      "is_default": true
    }
  ],
  "release_date": "2022-06-02",
  "themes": [
    {
      "slug": "carnival",
      "name": "Carnival"
    },
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "zombies",
      "name": "Zombies"
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
      "slug": "mystery_symbol",
      "name": "Mystery Symbol"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/zombie-carnival-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/zombie-carnival-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/zombie-carnival-b7/demand/
```

**12-month volume (illustrative):** 5,780 · **trend:** declining · YoY -20.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 560 | flat |
| Greece | 550 | flat |
| India | 260 | declining |
| Finland | 240 | flat |
| United States | 220 | flat |
| Canada | 180 | flat |
| Switzerland | 180 | flat |
| United Kingdom | 170 | flat |
| Malaysia | 160 | flat |
| Peru | 160 | flat |

> Full per-country breakdown (53 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/zombie-carnival-b7/
- **Public page:** https://i-gaming.tools/slot-games/zombie-carnival-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
