# Escape the Pyramid – Fire & Ice

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/escape-the-pyramid-fire-ice-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/escape-the-pyramid-fire-ice-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/escape-the-pyramid-fire-ice-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/escape-the-pyramid-fire-ice-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/escape-the-pyramid-fire-ice-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "escape-the-pyramid-fire-ice-b7",
  "name": "Escape the Pyramid – Fire & Ice",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
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
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "scatter_pays",
  "reels": 6,
  "rows": 6,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Ice & Fire",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2025-01-30",
  "themes": [
    {
      "slug": "adventure",
      "name": "Adventure"
    },
    {
      "slug": "egyptian",
      "name": "Egyptian"
    },
    {
      "slug": "fire",
      "name": "Fire"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "respin",
      "name": "Respin"
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
      "page_url": "https://i-gaming.tools/slot-games/escape-the-pyramid-fire-ice-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/escape-the-pyramid-fire-ice-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/escape-the-pyramid-fire-ice-b7/demand/
```

**12-month volume (illustrative):** 1,010 · **trend:** declining · YoY -50.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 120 | flat |
| Brazil | 110 | flat |
| Greece | 100 | flat |
| Switzerland | 90 | flat |
| Denmark | 40 | flat |
| India | 40 | flat |
| Malaysia | 40 | flat |
| South Africa | 40 | flat |
| United Kingdom | 40 | declining |
| Peru | 30 | declining |

> Full per-country breakdown (31 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/escape-the-pyramid-fire-ice-b7/
- **Public page:** https://i-gaming.tools/slot-games/escape-the-pyramid-fire-ice-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
