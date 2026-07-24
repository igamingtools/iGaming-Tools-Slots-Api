# Rabbit Garden

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/rabbit-garden-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rabbit-garden-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/rabbit-garden-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/rabbit-garden-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/rabbit-garden-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "rabbit-garden-b7",
  "name": "Rabbit Garden",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.05",
  "rtp_variants": [
    {
      "rtp": "96.05",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.08",
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
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2023-03-23",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "farm",
      "name": "Farm"
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
      "slug": "level-progression",
      "name": "Level Progression"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/rabbit-garden-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/rabbit-garden-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rabbit-garden-b7/demand/
```

**12-month volume (illustrative):** 7,730 · **trend:** declining · YoY -22.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 2,500 | declining |
| Philippines | 330 | flat |
| Spain | 330 | flat |
| Kazakhstan | 310 | flat |
| Switzerland | 300 | growing |
| Canada | 240 | flat |
| France | 210 | declining |
| Indonesia | 210 | flat |
| Portugal | 190 | flat |
| Turkey | 180 | flat |

> Full per-country breakdown (51 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/rabbit-garden-b7/
- **Public page:** https://i-gaming.tools/slot-games/rabbit-garden-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
