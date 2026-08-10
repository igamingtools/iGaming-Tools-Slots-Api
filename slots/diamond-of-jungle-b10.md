# Diamond of Jungle

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/diamond-of-jungle-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/diamond-of-jungle-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/diamond-of-jungle-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/diamond-of-jungle-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/diamond-of-jungle-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "diamond-of-jungle-b10",
  "name": "Diamond of Jungle",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "97.04",
  "rtp_variants": [
    {
      "rtp": "97.04",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.01",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "97.00",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "ways",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "75.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins",
      "cost": "150.00",
      "is_default": false
    }
  ],
  "release_date": "2024-03-21",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "gems",
      "name": "Gems"
    },
    {
      "slug": "jungle",
      "name": "Jungle"
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
      "slug": "scatter",
      "name": "Scatter"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/diamond-of-jungle-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/diamond-of-jungle-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/diamond-of-jungle-b10/demand/
```

**12-month volume (illustrative):** 630 · **trend:** declining · YoY -24.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 60 | flat |
| Poland | 60 | growing |
| Brazil | 50 | declining |
| Hungary | 50 | declining |
| Netherlands | 40 | growing |
| Romania | 40 | flat |
| Sweden | 40 | declining |
| Australia | 30 | growing |
| Latvia | 30 | declining |
| United Kingdom | 30 | flat |

> Full per-country breakdown (24 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/diamond-of-jungle-b10/
- **Public page:** https://i-gaming.tools/slot-games/diamond-of-jungle-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
