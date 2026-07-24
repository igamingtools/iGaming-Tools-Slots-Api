# Floating Dragon Megaways

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/floating-dragon-megaways-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/floating-dragon-megaways-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/floating-dragon-megaways-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/floating-dragon-megaways-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/floating-dragon-megaways-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "floating-dragon-megaways-b7",
  "name": "Floating Dragon Megaways",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.70",
  "rtp_variants": [
    {
      "rtp": "96.70",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.70",
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
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Hold & Spin",
      "cost": "120.00",
      "is_default": false
    }
  ],
  "release_date": "2022-09-01",
  "themes": [
    {
      "slug": "asian",
      "name": "Asian"
    },
    {
      "slug": "chinese",
      "name": "Chinese"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    },
    {
      "slug": "megaways",
      "name": "Megaways"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/floating-dragon-megaways-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  },
  "series": {
    "slug": "floating-dragon",
    "name": "Floating Dragon"
  }
}
```

## Search Demand

`GET /api/v1/slots/floating-dragon-megaways-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/floating-dragon-megaways-b7/demand/
```

**12-month volume (illustrative):** 2,340 · **trend:** declining · YoY -10.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 180 | declining |
| United States | 160 | declining |
| United Kingdom | 130 | declining |
| Brazil | 120 | flat |
| Greece | 120 | declining |
| Malaysia | 120 | growing |
| Australia | 110 | declining |
| Finland | 100 | flat |
| Argentina | 90 | flat |
| Slovakia | 90 | flat |

> Full per-country breakdown (41 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/floating-dragon-megaways-b7/
- **Public page:** https://i-gaming.tools/slot-games/floating-dragon-megaways-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
