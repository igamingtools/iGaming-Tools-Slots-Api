# Chicken Rush

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/chicken-rush-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chicken-rush-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/chicken-rush-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/chicken-rush-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/chicken-rush-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "chicken-rush-b10",
  "name": "Chicken Rush",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "97.00",
  "rtp_variants": [
    {
      "rtp": "97.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "med_high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Bronze",
      "cost": "50.00",
      "is_default": true
    },
    {
      "label": "Silver",
      "cost": "100.00",
      "is_default": false
    }
  ],
  "release_date": "2024-05-15",
  "themes": [
    {
      "slug": "western",
      "name": "Western"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/chicken-rush-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/chicken-rush-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chicken-rush-b10/demand/
```

**12-month volume (illustrative):** 5,420 · **trend:** declining · YoY -17.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 1,300 | flat |
| United Kingdom | 440 | declining |
| Romania | 390 | declining |
| Switzerland | 390 | flat |
| Finland | 300 | flat |
| Canada | 280 | flat |
| Germany | 270 | flat |
| Greece | 190 | declining |
| Hungary | 140 | flat |
| Netherlands | 140 | flat |

> Full per-country breakdown (33 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/chicken-rush-b10/
- **Public page:** https://i-gaming.tools/slot-games/chicken-rush-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
