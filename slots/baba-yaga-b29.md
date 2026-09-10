# Baba Yaga

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/baba-yaga-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/baba-yaga-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/baba-yaga-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/baba-yaga-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/baba-yaga-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "baba-yaga-b29",
  "name": "Baba Yaga",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.69",
  "rtp_variants": [
    {
      "rtp": "96.69",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.53",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.64",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "lines",
  "reels": 6,
  "rows": 4,
  "jackpot_type": "progressive",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Feature",
      "cost": "63.96",
      "is_default": true
    }
  ],
  "release_date": "2024-10-29",
  "themes": [
    {
      "slug": "fairy-tale",
      "name": "Fairy Tale"
    },
    {
      "slug": "witchcraft",
      "name": "Witchcraft"
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
      "slug": "random-wilds",
      "name": "Random Wilds"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/baba-yaga-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/baba-yaga-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/baba-yaga-b29/demand/
```

**12-month volume (illustrative):** 2,240 · **trend:** declining · YoY -22.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 950 | growing |
| Ukraine | 400 | flat |
| Netherlands | 110 | flat |
| India | 100 | declining |
| Latvia | 80 | growing |
| United States | 80 | flat |
| Greece | 70 | growing |
| Lithuania | 40 | growing |
| Poland | 40 | flat |
| Brazil | 30 | flat |

> Full per-country breakdown (33 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/baba-yaga-b29/
- **Public page:** https://i-gaming.tools/slot-games/baba-yaga-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
