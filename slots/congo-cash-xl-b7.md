# Congo Cash XL

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/congo-cash-xl-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/congo-cash-xl-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/congo-cash-xl-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/congo-cash-xl-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/congo-cash-xl-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "congo-cash-xl-b7",
  "name": "Congo Cash XL",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.41",
  "rtp_variants": [
    {
      "rtp": "96.41",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.51",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Feature",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2024-09-19",
  "themes": [
    {
      "slug": "africa",
      "name": "Africa"
    },
    {
      "slug": "animals",
      "name": "Animals"
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
      "slug": "modifier-reel",
      "name": "Modifier Reel"
    },
    {
      "slug": "wild",
      "name": "Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/congo-cash-xl-b7/"
    }
  },
  "series": {
    "slug": "congo-cash",
    "name": "Congo Cash"
  }
}
```

## Search Demand

`GET /api/v1/slots/congo-cash-xl-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/congo-cash-xl-b7/demand/
```

**12-month volume (illustrative):** 3,130 · **trend:** declining · YoY -53.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Argentina | 600 | declining |
| South Africa | 410 | declining |
| Netherlands | 300 | declining |
| United Kingdom | 210 | flat |
| United States | 130 | declining |
| Canada | 100 | declining |
| Finland | 80 | flat |
| Greece | 80 | flat |
| Brazil | 70 | flat |
| Indonesia | 70 | declining |

> Full per-country breakdown (44 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/congo-cash-xl-b7/
- **Public page:** https://i-gaming.tools/slot-games/congo-cash-xl-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
