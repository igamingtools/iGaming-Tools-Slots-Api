# Oracle of Gold

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/oracle-of-gold-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/oracle-of-gold-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/oracle-of-gold-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/oracle-of-gold-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/oracle-of-gold-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "oracle-of-gold-b7",
  "name": "Oracle of Gold",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.55",
  "rtp_variants": [
    {
      "rtp": "96.55",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.55",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.55",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "cluster",
  "reels": 6,
  "rows": 6,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Buy Super Free Spins",
      "cost": "400.00",
      "is_default": false
    }
  ],
  "release_date": "2025-11-03",
  "themes": [
    {
      "slug": "ancient-greece",
      "name": "Ancient Greece"
    },
    {
      "slug": "mythology",
      "name": "Mythology"
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
      "page_url": "https://i-gaming.tools/slot-games/oracle-of-gold-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/oracle-of-gold-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/oracle-of-gold-b7/demand/
```

**12-month volume (illustrative):** 3,660 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 380 | flat |
| Brazil | 300 | flat |
| United States | 220 | declining |
| Philippines | 200 | growing |
| Canada | 180 | flat |
| Switzerland | 180 | flat |
| Germany | 110 | declining |
| Indonesia | 100 | declining |
| Malaysia | 100 | growing |
| Netherlands | 90 | declining |

> Full per-country breakdown (51 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/oracle-of-gold-b7/
- **Public page:** https://i-gaming.tools/slot-games/oracle-of-gold-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
