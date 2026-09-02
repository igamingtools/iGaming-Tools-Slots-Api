# Wild Swarm 3 Chocolate Eggs

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wild-swarm-3-chocolate-eggs-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-swarm-3-chocolate-eggs-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wild-swarm-3-chocolate-eggs-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wild-swarm-3-chocolate-eggs-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wild-swarm-3-chocolate-eggs-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wild-swarm-3-chocolate-eggs-b28",
  "name": "Wild Swarm 3 Chocolate Eggs",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.48",
  "rtp_variants": [
    {
      "rtp": "96.48",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "94.33",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "low",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-03-11",
  "themes": [
    {
      "slug": "bees",
      "name": "Bees"
    },
    {
      "slug": "easter",
      "name": "Easter"
    },
    {
      "slug": "sweets",
      "name": "Sweets"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier-spots",
      "name": "Multiplier Spots"
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
      "page_url": "https://i-gaming.tools/slot-games/wild-swarm-3-chocolate-eggs-b28/"
    }
  },
  "series": {
    "slug": "wild-swarm",
    "name": "Wild Swarm"
  }
}
```

## Search Demand

`GET /api/v1/slots/wild-swarm-3-chocolate-eggs-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-swarm-3-chocolate-eggs-b28/demand/
```

**12-month volume (illustrative):** 460 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 60 | flat |
| Brazil | 50 | flat |
| Sweden | 40 | declining |
| Italy | 30 | declining |
| Netherlands | 30 | flat |
| Belgium | 20 | flat |
| Canada | 20 | flat |
| Denmark | 20 | declining |
| Greece | 20 | flat |
| India | 20 | growing |

> Full per-country breakdown (22 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wild-swarm-3-chocolate-eggs-b28/
- **Public page:** https://i-gaming.tools/slot-games/wild-swarm-3-chocolate-eggs-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
