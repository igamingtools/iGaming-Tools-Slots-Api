# Crystal Catcher

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/crystal-catcher-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/crystal-catcher-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/crystal-catcher-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/crystal-catcher-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/crystal-catcher-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "crystal-catcher-b28",
  "name": "Crystal Catcher",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.30",
  "rtp_variants": [
    {
      "rtp": "96.30",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.40",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "cluster",
  "reels": 7,
  "rows": 7,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Normal Bonus",
      "cost": "75.00",
      "is_default": true
    },
    {
      "label": "Super Bonus",
      "cost": "275.00",
      "is_default": false
    }
  ],
  "release_date": "2023-06-20",
  "themes": [
    {
      "slug": "gems",
      "name": "Gems"
    },
    {
      "slug": "mining",
      "name": "Mining"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
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
      "page_url": "https://i-gaming.tools/slot-games/crystal-catcher-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/crystal-catcher-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/crystal-catcher-b28/demand/
```

**12-month volume (illustrative):** 1,100 · **trend:** declining · YoY -32.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Canada | 120 | declining |
| Finland | 100 | growing |
| Germany | 100 | flat |
| Greece | 100 | growing |
| India | 100 | growing |
| Netherlands | 50 | growing |
| Sweden | 50 | declining |
| Australia | 40 | declining |
| Brazil | 40 | flat |
| Denmark | 40 | declining |

> Full per-country breakdown (29 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/crystal-catcher-b28/
- **Public page:** https://i-gaming.tools/slot-games/crystal-catcher-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
