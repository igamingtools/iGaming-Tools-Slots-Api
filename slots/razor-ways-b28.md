# Razor Ways

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/razor-ways-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/razor-ways-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/razor-ways-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/razor-ways-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/razor-ways-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "razor-ways-b28",
  "name": "Razor Ways",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.36",
  "rtp_variants": [
    {
      "rtp": "96.36",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.44",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.48",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Converter into Wild",
      "cost": "67.00",
      "is_default": true
    },
    {
      "label": "Razor Reveal",
      "cost": "50.00",
      "is_default": false
    }
  ],
  "release_date": "2024-08-07",
  "themes": [
    {
      "slug": "ocean",
      "name": "Ocean"
    },
    {
      "slug": "sharks",
      "name": "Sharks"
    },
    {
      "slug": "treasure",
      "name": "Treasure"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/razor-ways-b28/"
    }
  },
  "series": {
    "slug": "razor",
    "name": "Razor"
  }
}
```

## Search Demand

`GET /api/v1/slots/razor-ways-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/razor-ways-b28/demand/
```

**12-month volume (illustrative):** 10,220 · **trend:** declining · YoY -48.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 1,800 | flat |
| United States | 1,180 | flat |
| United Kingdom | 740 | flat |
| Switzerland | 570 | flat |
| Netherlands | 560 | flat |
| Greece | 410 | growing |
| Sweden | 410 | declining |
| Canada | 400 | flat |
| Denmark | 360 | declining |
| Finland | 280 | flat |

> Full per-country breakdown (60 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/razor-ways-b28/
- **Public page:** https://i-gaming.tools/slot-games/razor-ways-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
