# Fruity Halloween

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fruity-halloween-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fruity-halloween-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fruity-halloween-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fruity-halloween-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fruity-halloween-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fruity-halloween-b29",
  "name": "Fruity Halloween",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.61",
  "rtp_variants": [
    {
      "rtp": "96.61",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.67",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.93",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "scatter_pays",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "progressive",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Games",
      "cost": "60.00",
      "is_default": true
    }
  ],
  "release_date": "2023-10-31",
  "themes": [
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "halloween",
      "name": "Halloween"
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
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/fruity-halloween-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fruity-halloween-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fruity-halloween-b29/demand/
```

**12-month volume (illustrative):** 1,480 · **trend:** declining · YoY -42.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 1,210 | growing |
| India | 60 | flat |
| Brazil | 40 | flat |
| Indonesia | 30 | declining |
| Lithuania | 20 | growing |
| Tunisia | 20 | flat |
| Argentina | 10 | flat |
| Colombia | 10 | flat |
| Germany | 10 | flat |
| Honduras | 10 | flat |

> Full per-country breakdown (16 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fruity-halloween-b29/
- **Public page:** https://i-gaming.tools/slot-games/fruity-halloween-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
