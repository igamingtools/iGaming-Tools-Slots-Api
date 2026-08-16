# Forgotten

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/forgotten-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/forgotten-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/forgotten-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/forgotten-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/forgotten-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "forgotten-b10",
  "name": "Forgotten",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.89",
  "rtp_variants": [
    {
      "rtp": "96.89",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.03",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.90",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "unknown",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Bonus: 1 Symbol",
      "cost": "108.00",
      "is_default": true
    },
    {
      "label": "Buy Bonus: 2 Symbols",
      "cost": "170.00",
      "is_default": false
    }
  ],
  "release_date": "2024-10-29",
  "themes": [
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "toys",
      "name": "Toys"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "expanding-symbols",
      "name": "Expanding Symbols"
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
      "page_url": "https://i-gaming.tools/slot-games/forgotten-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/forgotten-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/forgotten-b10/demand/
```

**12-month volume (illustrative):** 3,390 · **trend:** declining · YoY -9.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 400 | declining |
| Canada | 160 | declining |
| Finland | 140 | flat |
| Brazil | 130 | declining |
| Indonesia | 120 | declining |
| Germany | 110 | declining |
| Mexico | 110 | declining |
| Peru | 110 | declining |
| Argentina | 100 | flat |
| Spain | 100 | flat |

> Full per-country breakdown (54 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/forgotten-b10/
- **Public page:** https://i-gaming.tools/slot-games/forgotten-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
