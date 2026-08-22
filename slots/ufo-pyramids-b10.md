# UFO Pyramids

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/ufo-pyramids-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/ufo-pyramids-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/ufo-pyramids-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/ufo-pyramids-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/ufo-pyramids-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "ufo-pyramids-b10",
  "name": "UFO Pyramids",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "97.17",
  "rtp_variants": [
    {
      "rtp": "97.17",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.17",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "scatter_pays",
  "reels": 8,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2025-12-16",
  "themes": [
    {
      "slug": "aliens",
      "name": "Aliens"
    },
    {
      "slug": "egyptian",
      "name": "Egyptian"
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
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/ufo-pyramids-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/ufo-pyramids-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/ufo-pyramids-b10/demand/
```

**12-month volume (illustrative):** 430 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 40 | flat |
| Germany | 30 | growing |
| Poland | 30 | flat |
| United Kingdom | 30 | declining |
| Australia | 20 | declining |
| Belarus | 20 | flat |
| Brazil | 20 | growing |
| Colombia | 20 | flat |
| Cyprus | 20 | growing |
| Italy | 20 | flat |

> Full per-country breakdown (25 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/ufo-pyramids-b10/
- **Public page:** https://i-gaming.tools/slot-games/ufo-pyramids-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
