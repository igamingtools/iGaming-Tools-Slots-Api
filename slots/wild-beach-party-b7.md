# Wild Beach Party

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wild-beach-party-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-beach-party-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wild-beach-party-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wild-beach-party-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wild-beach-party-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wild-beach-party-b7",
  "name": "Wild Beach Party",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.53",
  "rtp_variants": [
    {
      "rtp": "96.53",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.45",
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
  "release_date": "2022-03-10",
  "themes": [
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "party",
      "name": "Party"
    },
    {
      "slug": "tropical",
      "name": "Tropical"
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
      "page_url": "https://i-gaming.tools/slot-games/wild-beach-party-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/wild-beach-party-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-beach-party-b7/demand/
```

**12-month volume (illustrative):** 4,190 · **trend:** flat · YoY +4.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 420 | flat |
| Finland | 240 | flat |
| Switzerland | 210 | flat |
| Canada | 180 | declining |
| India | 160 | declining |
| United States | 160 | flat |
| Denmark | 140 | declining |
| Greece | 140 | flat |
| Malaysia | 140 | flat |
| Philippines | 140 | flat |

> Full per-country breakdown (49 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wild-beach-party-b7/
- **Public page:** https://i-gaming.tools/slot-games/wild-beach-party-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
