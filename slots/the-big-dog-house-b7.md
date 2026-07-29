# The Big Dog House

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/the-big-dog-house-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/the-big-dog-house-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/the-big-dog-house-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/the-big-dog-house-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/the-big-dog-house-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "the-big-dog-house-b7",
  "name": "The Big Dog House",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.53",
  "rtp_variants": [
    {
      "rtp": "96.53",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.51",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.55",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "medium",
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
      "label": "Biggie Free Spins",
      "cost": "200.00",
      "is_default": false
    }
  ],
  "release_date": "2026-05-21",
  "themes": [
    {
      "slug": "dogs",
      "name": "Dogs"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "colossal-symbols",
      "name": "Colossal Symbols"
    },
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/the-big-dog-house-b7/"
    }
  },
  "series": {
    "slug": "the-dog-house",
    "name": "The Dog House"
  }
}
```

## Search Demand

`GET /api/v1/slots/the-big-dog-house-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/the-big-dog-house-b7/demand/
```

**12-month volume (illustrative):** 8,800 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 1,080 | growing |
| United Kingdom | 650 | declining |
| Netherlands | 550 | declining |
| Finland | 520 | declining |
| Canada | 440 | declining |
| Denmark | 420 | declining |
| Ukraine | 410 | declining |
| Germany | 380 | declining |
| Brazil | 310 | declining |
| Indonesia | 230 | declining |

> Full per-country breakdown (67 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/the-big-dog-house-b7/
- **Public page:** https://i-gaming.tools/slot-games/the-big-dog-house-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
