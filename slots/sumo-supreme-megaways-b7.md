# Sumo Supreme Megaways

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/sumo-supreme-megaways-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sumo-supreme-megaways-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/sumo-supreme-megaways-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/sumo-supreme-megaways-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/sumo-supreme-megaways-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "sumo-supreme-megaways-b7",
  "name": "Sumo Supreme Megaways",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.55",
  "rtp_variants": [
    {
      "rtp": "96.55",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.56",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.53",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "megaways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "75.00",
      "is_default": true
    }
  ],
  "release_date": "2024-08-01",
  "themes": [
    {
      "slug": "japanese",
      "name": "Japanese"
    },
    {
      "slug": "sports",
      "name": "Sports"
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
      "page_url": "https://i-gaming.tools/slot-games/sumo-supreme-megaways-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/sumo-supreme-megaways-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sumo-supreme-megaways-b7/demand/
```

**12-month volume (illustrative):** 2,190 · **trend:** declining · YoY -48.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 390 | declining |
| Malaysia | 140 | flat |
| Philippines | 140 | flat |
| Argentina | 100 | declining |
| Mexico | 100 | declining |
| Greece | 90 | declining |
| Switzerland | 90 | declining |
| Netherlands | 70 | declining |
| United Kingdom | 70 | flat |
| Canada | 60 | declining |

> Full per-country breakdown (47 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/sumo-supreme-megaways-b7/
- **Public page:** https://i-gaming.tools/slot-games/sumo-supreme-megaways-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
