# Sweet Bonanza 2500

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/sweet-bonanza-2500-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sweet-bonanza-2500-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/sweet-bonanza-2500-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/sweet-bonanza-2500-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/sweet-bonanza-2500-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "sweet-bonanza-2500-b7",
  "name": "Sweet Bonanza 2500",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.52",
  "rtp_variants": [
    {
      "rtp": "96.52",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.49",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.49",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "scatter_pays",
  "reels": 6,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins 1",
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2026-04-30",
  "themes": [
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "sweets",
      "name": "Sweets"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/sweet-bonanza-2500-b7/"
    }
  },
  "series": {
    "slug": "sweet-bonanza",
    "name": "Sweet Bonanza"
  }
}
```

## Search Demand

`GET /api/v1/slots/sweet-bonanza-2500-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/sweet-bonanza-2500-b7/demand/
```

**12-month volume (illustrative):** 59,140 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 6,740 | declining |
| South Africa | 6,270 | declining |
| Philippines | 5,440 | declining |
| Canada | 4,700 | declining |
| Greece | 3,840 | declining |
| Turkey | 3,590 | declining |
| Switzerland | 1,890 | declining |
| Indonesia | 1,810 | declining |
| United Kingdom | 1,800 | declining |
| Denmark | 1,730 | flat |

> Full per-country breakdown (76 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/sweet-bonanza-2500-b7/
- **Public page:** https://i-gaming.tools/slot-games/sweet-bonanza-2500-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
