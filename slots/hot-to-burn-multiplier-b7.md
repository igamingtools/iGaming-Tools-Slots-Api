# Hot to Burn Multiplier

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/hot-to-burn-multiplier-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hot-to-burn-multiplier-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/hot-to-burn-multiplier-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/hot-to-burn-multiplier-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/hot-to-burn-multiplier-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "hot-to-burn-multiplier-b7",
  "name": "Hot to Burn Multiplier",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.51",
  "rtp_variants": [
    {
      "rtp": "96.51",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-06-24",
  "themes": [
    {
      "slug": "classic",
      "name": "Classic"
    },
    {
      "slug": "fire",
      "name": "Fire"
    },
    {
      "slug": "fruits",
      "name": "Fruits"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
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
      "page_url": "https://i-gaming.tools/slot-games/hot-to-burn-multiplier-b7/"
    }
  },
  "studio": {
    "slug": "reel-kingdom",
    "name": "Reel Kingdom"
  },
  "series": {
    "slug": "hot-to-burn",
    "name": "Hot to Burn"
  }
}
```

## Search Demand

`GET /api/v1/slots/hot-to-burn-multiplier-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hot-to-burn-multiplier-b7/demand/
```

**12-month volume (illustrative):** 860 · **trend:** declining · YoY -41.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 70 | flat |
| Mexico | 70 | declining |
| Germany | 50 | flat |
| Belgium | 40 | flat |
| Finland | 40 | flat |
| Greece | 40 | flat |
| India | 40 | flat |
| Ireland | 40 | flat |
| Peru | 40 | flat |
| Romania | 40 | growing |

> Full per-country breakdown (34 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/hot-to-burn-multiplier-b7/
- **Public page:** https://i-gaming.tools/slot-games/hot-to-burn-multiplier-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
