# Retro Sweets

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/retro-sweets-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/retro-sweets-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/retro-sweets-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/retro-sweets-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/retro-sweets-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "retro-sweets-b28",
  "name": "Retro Sweets",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.49",
  "rtp_variants": [
    {
      "rtp": "96.49",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.05",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.31",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 6,
  "rows": 9,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Normal Free Spins Feature",
      "cost": "120.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins Feature",
      "cost": "400.00",
      "is_default": false
    }
  ],
  "release_date": "2024-05-02",
  "themes": [
    {
      "slug": "neon",
      "name": "Neon"
    },
    {
      "slug": "sweets",
      "name": "Sweets"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
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
      "page_url": "https://i-gaming.tools/slot-games/retro-sweets-b28/"
    }
  },
  "series": {
    "slug": "retro",
    "name": "Retro"
  }
}
```

## Search Demand

`GET /api/v1/slots/retro-sweets-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/retro-sweets-b28/demand/
```

**12-month volume (illustrative):** 18,970 · **trend:** declining · YoY -25.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Denmark | 2,070 | declining |
| Greece | 1,510 | growing |
| United Kingdom | 1,430 | growing |
| Finland | 1,360 | flat |
| Sweden | 1,210 | growing |
| Canada | 1,060 | flat |
| Brazil | 830 | growing |
| Germany | 720 | flat |
| Netherlands | 580 | flat |
| Norway | 560 | flat |

> Full per-country breakdown (69 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/retro-sweets-b28/
- **Public page:** https://i-gaming.tools/slot-games/retro-sweets-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
