# Medusa's Stone

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/medusa-s-stone-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/medusa-s-stone-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/medusa-s-stone-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/medusa-s-stone-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/medusa-s-stone-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "medusa-s-stone-b7",
  "name": "Medusa's Stone",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.46",
  "rtp_variants": [
    {
      "rtp": "96.46",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.53",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "75.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins",
      "cost": "200.00",
      "is_default": false
    }
  ],
  "release_date": "2024-06-13",
  "themes": [
    {
      "slug": "ancient-greece",
      "name": "Ancient Greece"
    },
    {
      "slug": "snakes",
      "name": "Snakes"
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
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/medusa-s-stone-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/medusa-s-stone-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/medusa-s-stone-b7/demand/
```

**12-month volume (illustrative):** 540 · **trend:** declining · YoY -18.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Switzerland | 90 | flat |
| Germany | 70 | flat |
| Brazil | 40 | flat |
| Greece | 40 | growing |
| Philippines | 30 | growing |
| Sweden | 30 | flat |
| United Kingdom | 30 | flat |
| Argentina | 20 | flat |
| Croatia | 20 | flat |
| Latvia | 20 | declining |

> Full per-country breakdown (23 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/medusa-s-stone-b7/
- **Public page:** https://i-gaming.tools/slot-games/medusa-s-stone-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
