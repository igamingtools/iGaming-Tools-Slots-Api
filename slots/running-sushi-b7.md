# Running Sushi

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/running-sushi-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/running-sushi-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/running-sushi-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/running-sushi-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/running-sushi-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "running-sushi-b7",
  "name": "Running Sushi",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.00",
  "rtp_variants": [
    {
      "rtp": "96.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "85.00",
      "is_default": true
    }
  ],
  "release_date": "2024-08-08",
  "themes": [
    {
      "slug": "asian",
      "name": "Asian"
    },
    {
      "slug": "food",
      "name": "Food"
    },
    {
      "slug": "japanese",
      "name": "Japanese"
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
      "slug": "money-collect",
      "name": "Money Collect"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/running-sushi-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/running-sushi-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/running-sushi-b7/demand/
```

**12-month volume (illustrative):** 2,130 · **trend:** declining · YoY -54.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 380 | declining |
| Switzerland | 270 | growing |
| Philippines | 160 | flat |
| Brazil | 120 | flat |
| Finland | 100 | growing |
| Germany | 70 | growing |
| Romania | 70 | flat |
| Canada | 60 | flat |
| Malaysia | 60 | flat |
| Peru | 60 | growing |

> Full per-country breakdown (39 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/running-sushi-b7/
- **Public page:** https://i-gaming.tools/slot-games/running-sushi-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
