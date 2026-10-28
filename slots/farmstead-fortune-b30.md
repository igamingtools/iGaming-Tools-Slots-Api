# Farmstead Fortune

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/farmstead-fortune-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/farmstead-fortune-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/farmstead-fortune-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/farmstead-fortune-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/farmstead-fortune-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "farmstead-fortune-b30",
  "name": "Farmstead Fortune",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.76",
  "rtp_variants": [
    {
      "rtp": "96.76",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-08-01",
  "themes": [
    {
      "slug": "farm",
      "name": "Farm"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
    },
    {
      "slug": "growing-reels",
      "name": "Growing Reels"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/farmstead-fortune-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/farmstead-fortune-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/farmstead-fortune-b30/demand/
```

**12-month volume (illustrative):** 1,620 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 800 | growing |
| Philippines | 180 | declining |
| Indonesia | 150 | declining |
| India | 60 | growing |
| Thailand | 50 | declining |
| Pakistan | 40 | flat |
| Canada | 20 | declining |
| Germany | 20 | flat |
| Malaysia | 20 | declining |
| Mexico | 20 | flat |

> Full per-country breakdown (33 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/farmstead-fortune-b30/
- **Public page:** https://i-gaming.tools/slot-games/farmstead-fortune-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
