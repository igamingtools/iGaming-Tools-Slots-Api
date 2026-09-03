# Sea of Spirits

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/sea-of-spirits-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sea-of-spirits-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/sea-of-spirits-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/sea-of-spirits-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/sea-of-spirits-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "sea-of-spirits-b28",
  "name": "Sea of Spirits",
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
      "rtp": "96.23",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.41",
      "variant": "ante_bet",
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
      "label": "Bonus Feature",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Bonus Feature",
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2025-11-19",
  "themes": [
    {
      "slug": "ghosts",
      "name": "Ghosts"
    },
    {
      "slug": "ocean",
      "name": "Ocean"
    },
    {
      "slug": "pirates",
      "name": "Pirates"
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
      "slug": "one-shot-collect",
      "name": "One-shot Collect"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/sea-of-spirits-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/sea-of-spirits-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sea-of-spirits-b28/demand/
```

**12-month volume (illustrative):** 2,520 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 160 | declining |
| Denmark | 130 | declining |
| Canada | 120 | flat |
| Greece | 120 | declining |
| United States | 120 | declining |
| Netherlands | 110 | flat |
| Germany | 90 | flat |
| Sweden | 90 | flat |
| Switzerland | 90 | flat |
| United Kingdom | 90 | flat |

> Full per-country breakdown (46 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/sea-of-spirits-b28/
- **Public page:** https://i-gaming.tools/slot-games/sea-of-spirits-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
