# Fly\!

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fly-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fly-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fly-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fly-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fly-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fly-b29",
  "name": "Fly!",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.88",
  "rtp_variants": [
    {
      "rtp": "96.88",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "cluster",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2021-09-28",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "carnival",
      "name": "Carnival"
    },
    {
      "slug": "party",
      "name": "Party"
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
      "slug": "retrigger",
      "name": "Retrigger"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/fly-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fly-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fly-b29/demand/
```

**12-month volume (illustrative):** 15,640 · **trend:** declining · YoY -10.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 3,300 | growing |
| India | 2,580 | flat |
| Philippines | 1,560 | growing |
| South Africa | 450 | flat |
| Indonesia | 340 | growing |
| Switzerland | 300 | growing |
| Canada | 260 | flat |
| Malaysia | 240 | flat |
| Pakistan | 220 | flat |
| Thailand | 220 | flat |

> Full per-country breakdown (79 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fly-b29/
- **Public page:** https://i-gaming.tools/slot-games/fly-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
