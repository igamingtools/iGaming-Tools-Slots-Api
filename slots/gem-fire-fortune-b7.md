# Gem Fire Fortune

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/gem-fire-fortune-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gem-fire-fortune-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/gem-fire-fortune-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/gem-fire-fortune-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/gem-fire-fortune-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "gem-fire-fortune-b7",
  "name": "Gem Fire Fortune",
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
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.49",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 7,
  "rows": 7,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins",
      "cost": "400.00",
      "is_default": false
    }
  ],
  "release_date": "2025-06-30",
  "themes": [
    {
      "slug": "fire",
      "name": "Fire"
    },
    {
      "slug": "gems",
      "name": "Gems"
    }
  ],
  "features": [
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/gem-fire-fortune-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/gem-fire-fortune-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gem-fire-fortune-b7/demand/
```

**12-month volume (illustrative):** 2,930 · **trend:** growing · YoY +845.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 590 | growing |
| Greece | 340 | growing |
| Philippines | 120 | growing |
| Switzerland | 120 | flat |
| India | 100 | growing |
| Malaysia | 100 | growing |
| Peru | 100 | flat |
| Australia | 80 | flat |
| Germany | 80 | growing |
| Indonesia | 70 | flat |

> Full per-country breakdown (50 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/gem-fire-fortune-b7/
- **Public page:** https://i-gaming.tools/slot-games/gem-fire-fortune-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
