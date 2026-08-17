# Rocket Eruption: Triple Blast

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/rocket-eruption-triple-blast-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rocket-eruption-triple-blast-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/rocket-eruption-triple-blast-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/rocket-eruption-triple-blast-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/rocket-eruption-triple-blast-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "rocket-eruption-triple-blast-b10",
  "name": "Rocket Eruption: Triple Blast",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.57",
  "rtp_variants": [
    {
      "rtp": "96.57",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Bonus Buy",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Bonus Buy",
      "cost": "200.00",
      "is_default": false
    }
  ],
  "release_date": "2026-02-24",
  "themes": [
    {
      "slug": "dinosaurs",
      "name": "Dinosaurs"
    },
    {
      "slug": "fire",
      "name": "Fire"
    },
    {
      "slug": "tropical",
      "name": "Tropical"
    }
  ],
  "features": [
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
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
      "page_url": "https://i-gaming.tools/slot-games/rocket-eruption-triple-blast-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/rocket-eruption-triple-blast-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rocket-eruption-triple-blast-b10/demand/
```

**12-month volume (illustrative):** 550 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 100 | declining |
| United States | 80 | declining |
| Greece | 40 | declining |
| United Kingdom | 40 | declining |
| Germany | 30 | declining |
| Netherlands | 30 | declining |
| Qatar | 30 | flat |
| Australia | 20 | declining |
| Brazil | 20 | flat |
| Ireland | 20 | flat |

> Full per-country breakdown (20 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/rocket-eruption-triple-blast-b10/
- **Public page:** https://i-gaming.tools/slot-games/rocket-eruption-triple-blast-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
