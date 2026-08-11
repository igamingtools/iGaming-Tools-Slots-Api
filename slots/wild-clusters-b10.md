# Wild Clusters

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wild-clusters-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-clusters-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wild-clusters-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wild-clusters-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wild-clusters-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wild-clusters-b10",
  "name": "Wild Clusters",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.82",
  "rtp_variants": [
    {
      "rtp": "96.82",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.82",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.68",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "cluster",
  "reels": 7,
  "rows": 7,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Wild Boost X3",
      "cost": "6.00",
      "is_default": true
    },
    {
      "label": "Wild Boost X5",
      "cost": "24.00",
      "is_default": false
    }
  ],
  "release_date": "2025-04-01",
  "themes": [
    {
      "slug": "gems",
      "name": "Gems"
    },
    {
      "slug": "space",
      "name": "Space"
    }
  ],
  "features": [
    {
      "slug": "cluster_pays",
      "name": "Cluster Pays"
    },
    {
      "slug": "colossal-symbols",
      "name": "Colossal Symbols"
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
      "page_url": "https://i-gaming.tools/slot-games/wild-clusters-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/wild-clusters-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-clusters-b10/demand/
```

**12-month volume (illustrative):** 2,440 · **trend:** growing · YoY +151.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 320 | flat |
| Canada | 280 | declining |
| Finland | 220 | flat |
| Germany | 190 | declining |
| United Kingdom | 170 | flat |
| Norway | 160 | declining |
| Netherlands | 150 | flat |
| Poland | 140 | flat |
| France | 120 | flat |
| Italy | 120 | flat |

> Full per-country breakdown (27 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wild-clusters-b10/
- **Public page:** https://i-gaming.tools/slot-games/wild-clusters-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
