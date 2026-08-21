# Santa's Wonderland

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/santa-s-wonderland-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/santa-s-wonderland-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/santa-s-wonderland-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/santa-s-wonderland-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/santa-s-wonderland-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "santa-s-wonderland-b7",
  "name": "Santa's Wonderland",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.23",
  "rtp_variants": [
    {
      "rtp": "96.23",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.38",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 8,
  "rows": 8,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Midnight Riches",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2021-11-29",
  "themes": [
    {
      "slug": "christmas",
      "name": "Christmas"
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
      "page_url": "https://i-gaming.tools/slot-games/santa-s-wonderland-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/santa-s-wonderland-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/santa-s-wonderland-b7/demand/
```

**12-month volume (illustrative):** 4,370 · **trend:** declining · YoY -21.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 320 | declining |
| Brazil | 290 | declining |
| Netherlands | 220 | declining |
| Denmark | 210 | declining |
| Sweden | 190 | declining |
| Belgium | 180 | flat |
| Finland | 160 | flat |
| Germany | 160 | flat |
| United States | 160 | flat |
| South Africa | 130 | declining |

> Full per-country breakdown (53 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/santa-s-wonderland-b7/
- **Public page:** https://i-gaming.tools/slot-games/santa-s-wonderland-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
