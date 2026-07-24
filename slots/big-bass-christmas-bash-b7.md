# Big Bass Christmas Bash

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/big-bass-christmas-bash-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-bass-christmas-bash-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/big-bass-christmas-bash-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/big-bass-christmas-bash-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/big-bass-christmas-bash-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "big-bass-christmas-bash-b7",
  "name": "Big Bass Christmas Bash",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.71",
  "rtp_variants": [
    {
      "rtp": "96.71",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.71",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.71",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2023-11-01",
  "themes": [
    {
      "slug": "christmas",
      "name": "Christmas"
    },
    {
      "slug": "fishing",
      "name": "Fishing"
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
      "page_url": "https://i-gaming.tools/slot-games/big-bass-christmas-bash-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  },
  "series": {
    "slug": "big-bass",
    "name": "Big Bass"
  }
}
```

## Search Demand

`GET /api/v1/slots/big-bass-christmas-bash-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-bass-christmas-bash-b7/demand/
```

**12-month volume (illustrative):** 7,260 · **trend:** declining · YoY -25.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 1,280 | declining |
| Brazil | 1,020 | declining |
| Greece | 590 | declining |
| Germany | 540 | declining |
| Canada | 380 | declining |
| United States | 280 | declining |
| Netherlands | 250 | declining |
| Switzerland | 240 | flat |
| Latvia | 150 | declining |
| Portugal | 150 | declining |

> Full per-country breakdown (47 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/big-bass-christmas-bash-b7/
- **Public page:** https://i-gaming.tools/slot-games/big-bass-christmas-bash-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
