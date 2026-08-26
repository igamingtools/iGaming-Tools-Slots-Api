# Bamboo Ways

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/bamboo-ways-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/bamboo-ways-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/bamboo-ways-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/bamboo-ways-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/bamboo-ways-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "bamboo-ways-b28",
  "name": "Bamboo Ways",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.30",
  "rtp_variants": [
    {
      "rtp": "96.30",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.36",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.37",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "variable_ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Mystery Symbols",
      "cost": "18.00",
      "is_default": true
    },
    {
      "label": "Grand Golden Bamboo",
      "cost": "120.00",
      "is_default": false
    }
  ],
  "release_date": "2025-09-03",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "panda",
      "name": "Panda"
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
      "page_url": "https://i-gaming.tools/slot-games/bamboo-ways-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/bamboo-ways-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/bamboo-ways-b28/demand/
```

**12-month volume (illustrative):** 5,410 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 630 | growing |
| Netherlands | 370 | flat |
| Finland | 340 | declining |
| Canada | 320 | flat |
| United Kingdom | 270 | flat |
| Denmark | 240 | flat |
| Switzerland | 240 | growing |
| United States | 200 | growing |
| Australia | 180 | flat |
| Italy | 180 | flat |

> Full per-country breakdown (57 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/bamboo-ways-b28/
- **Public page:** https://i-gaming.tools/slot-games/bamboo-ways-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
