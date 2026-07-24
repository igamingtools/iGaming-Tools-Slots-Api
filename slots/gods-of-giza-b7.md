# Gods of Giza

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/gods-of-giza-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gods-of-giza-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/gods-of-giza-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/gods-of-giza-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/gods-of-giza-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "gods-of-giza-b7",
  "name": "Gods of Giza",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.01",
  "rtp_variants": [
    {
      "rtp": "96.01",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.01",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2023-04-06",
  "themes": [
    {
      "slug": "egyptian",
      "name": "Egyptian"
    },
    {
      "slug": "mythology",
      "name": "Mythology"
    },
    {
      "slug": "treasure",
      "name": "Treasure"
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
      "page_url": "https://i-gaming.tools/slot-games/gods-of-giza-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/gods-of-giza-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gods-of-giza-b7/demand/
```

**12-month volume (illustrative):** 1,450 · **trend:** declining · YoY -8.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 120 | flat |
| Brazil | 110 | flat |
| Romania | 110 | flat |
| United States | 100 | declining |
| Indonesia | 70 | growing |
| Italy | 60 | flat |
| Switzerland | 60 | flat |
| Croatia | 50 | declining |
| Portugal | 50 | growing |
| Bulgaria | 40 | flat |

> Full per-country breakdown (38 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/gods-of-giza-b7/
- **Public page:** https://i-gaming.tools/slot-games/gods-of-giza-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
