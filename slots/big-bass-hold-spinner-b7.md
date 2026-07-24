# Big Bass – Hold & Spinner

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/big-bass-hold-spinner-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-bass-hold-spinner-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/big-bass-hold-spinner-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/big-bass-hold-spinner-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/big-bass-hold-spinner-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "big-bass-hold-spinner-b7",
  "name": "Big Bass – Hold & Spinner",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.07",
  "rtp_variants": [
    {
      "rtp": "96.07",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.09",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.07",
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
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Hold & Spinner",
      "cost": "100.00",
      "is_default": false
    }
  ],
  "release_date": "2023-03-27",
  "themes": [
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
      "page_url": "https://i-gaming.tools/slot-games/big-bass-hold-spinner-b7/"
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

`GET /api/v1/slots/big-bass-hold-spinner-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/big-bass-hold-spinner-b7/demand/
```

**12-month volume (illustrative):** 20,120 · **trend:** declining · YoY -7.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 5,170 | growing |
| United Kingdom | 5,030 | declining |
| Greece | 1,020 | declining |
| Germany | 960 | growing |
| Canada | 580 | growing |
| Netherlands | 470 | flat |
| Spain | 440 | declining |
| Switzerland | 420 | declining |
| Latvia | 340 | flat |
| United States | 320 | flat |

> Full per-country breakdown (56 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/big-bass-hold-spinner-b7/
- **Public page:** https://i-gaming.tools/slot-games/big-bass-hold-spinner-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
