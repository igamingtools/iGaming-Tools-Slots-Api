# Sticky Bees

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/sticky-bees-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sticky-bees-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/sticky-bees-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/sticky-bees-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/sticky-bees-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "sticky-bees-b7",
  "name": "Sticky Bees",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.06",
  "rtp_variants": [
    {
      "rtp": "96.06",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "95.99",
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
    }
  ],
  "release_date": "2023-05-01",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
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
      "page_url": "https://i-gaming.tools/slot-games/sticky-bees-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/sticky-bees-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sticky-bees-b7/demand/
```

**12-month volume (illustrative):** 8,070 · **trend:** declining · YoY -13.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Philippines | 1,890 | declining |
| Brazil | 690 | declining |
| Greece | 610 | declining |
| Peru | 530 | declining |
| Switzerland | 270 | declining |
| Malaysia | 260 | flat |
| Canada | 220 | declining |
| Indonesia | 190 | flat |
| Finland | 180 | declining |
| Germany | 180 | declining |

> Full per-country breakdown (51 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/sticky-bees-b7/
- **Public page:** https://i-gaming.tools/slot-games/sticky-bees-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
