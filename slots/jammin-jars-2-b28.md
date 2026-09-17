# Jammin' Jars 2

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/jammin-jars-2-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/jammin-jars-2-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/jammin-jars-2-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/jammin-jars-2-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/jammin-jars-2-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "jammin-jars-2-b28",
  "name": "Jammin' Jars 2",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.40",
  "rtp_variants": [
    {
      "rtp": "96.40",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.10",
      "variant": "feature",
      "is_default": false
    },
    {
      "rtp": "96.20",
      "variant": "feature",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 8,
  "rows": 8,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2021-06-02",
  "themes": [
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "music",
      "name": "Music"
    },
    {
      "slug": "neon",
      "name": "Neon"
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
      "page_url": "https://i-gaming.tools/slot-games/jammin-jars-2-b28/"
    }
  },
  "series": {
    "slug": "jammin-jars",
    "name": "Jammin' Jars"
  }
}
```

## Search Demand

`GET /api/v1/slots/jammin-jars-2-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/jammin-jars-2-b28/demand/
```

**12-month volume (illustrative):** 6,600 · **trend:** declining · YoY -31.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 860 | declining |
| United States | 400 | growing |
| Greece | 350 | flat |
| United Kingdom | 320 | declining |
| Switzerland | 270 | declining |
| Austria | 240 | declining |
| Finland | 240 | flat |
| Australia | 210 | growing |
| Canada | 200 | growing |
| Netherlands | 200 | flat |

> Full per-country breakdown (62 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/jammin-jars-2-b28/
- **Public page:** https://i-gaming.tools/slot-games/jammin-jars-2-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
