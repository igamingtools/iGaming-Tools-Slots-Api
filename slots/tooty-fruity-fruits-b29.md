# Tooty Fruity Fruits

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/tooty-fruity-fruits-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/tooty-fruity-fruits-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/tooty-fruity-fruits-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/tooty-fruity-fruits-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/tooty-fruity-fruits-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "tooty-fruity-fruits-b29",
  "name": "Tooty Fruity Fruits",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.67",
  "rtp_variants": [
    {
      "rtp": "96.67",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.91",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.75",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "progressive",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Feature",
      "cost": "51.00",
      "is_default": true
    }
  ],
  "release_date": "2023-07-10",
  "themes": [
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "jungle",
      "name": "Jungle"
    },
    {
      "slug": "tropical",
      "name": "Tropical"
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
      "page_url": "https://i-gaming.tools/slot-games/tooty-fruity-fruits-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/tooty-fruity-fruits-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/tooty-fruity-fruits-b29/demand/
```

**12-month volume (illustrative):** 820 · **trend:** declining · YoY -50.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 560 | growing |
| India | 60 | flat |
| Pakistan | 40 | flat |
| Tunisia | 30 | flat |
| Lithuania | 20 | flat |
| Malaysia | 20 | flat |
| Peru | 20 | flat |
| Algeria | 10 | flat |
| Australia | 10 | flat |
| Brazil | 10 | flat |

> Full per-country breakdown (14 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/tooty-fruity-fruits-b29/
- **Public page:** https://i-gaming.tools/slot-games/tooty-fruity-fruits-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
