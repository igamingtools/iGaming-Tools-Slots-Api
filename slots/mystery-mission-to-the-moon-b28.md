# Mystery Mission \- To The Moon

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mystery-mission-to-the-moon-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mystery-mission-to-the-moon-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mystery-mission-to-the-moon-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mystery-mission-to-the-moon-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mystery-mission-to-the-moon-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mystery-mission-to-the-moon-b28",
  "name": "Mystery Mission - To The Moon",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.25",
  "rtp_variants": [
    {
      "rtp": "96.25",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.21",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.30",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Three Scatters",
      "cost": "102.00",
      "is_default": true
    },
    {
      "label": "Four Scatters",
      "cost": "161.00",
      "is_default": false
    }
  ],
  "release_date": "2022-11-09",
  "themes": [
    {
      "slug": "aliens",
      "name": "Aliens"
    },
    {
      "slug": "robots",
      "name": "Robots"
    },
    {
      "slug": "space",
      "name": "Space"
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
      "page_url": "https://i-gaming.tools/slot-games/mystery-mission-to-the-moon-b28/"
    }
  },
  "series": {
    "slug": "mystery",
    "name": "Mystery"
  }
}
```

## Search Demand

`GET /api/v1/slots/mystery-mission-to-the-moon-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mystery-mission-to-the-moon-b28/demand/
```

**12-month volume (illustrative):** 3,060 · **trend:** declining · YoY -9.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 970 | growing |
| Germany | 200 | flat |
| United States | 180 | flat |
| Finland | 160 | flat |
| Netherlands | 110 | declining |
| Canada | 100 | declining |
| Greece | 100 | flat |
| Ireland | 100 | flat |
| Norway | 100 | flat |
| Romania | 90 | growing |

> Full per-country breakdown (42 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mystery-mission-to-the-moon-b28/
- **Public page:** https://i-gaming.tools/slot-games/mystery-mission-to-the-moon-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
