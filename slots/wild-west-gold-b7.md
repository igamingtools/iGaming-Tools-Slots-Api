# Wild West Gold

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/wild-west-gold-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-west-gold-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/wild-west-gold-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/wild-west-gold-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/wild-west-gold-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "wild-west-gold-b7",
  "name": "Wild West Gold",
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
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2020-03-26",
  "themes": [
    {
      "slug": "western",
      "name": "Western"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
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
      "page_url": "https://i-gaming.tools/slot-games/wild-west-gold-b7/"
    }
  },
  "series": {
    "slug": "wild-west-gold",
    "name": "Wild West Gold"
  }
}
```

## Search Demand

`GET /api/v1/slots/wild-west-gold-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/wild-west-gold-b7/demand/
```

**12-month volume (illustrative):** 26,000 · **trend:** declining · YoY -24.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 4,200 | flat |
| Indonesia | 2,150 | growing |
| Greece | 2,100 | growing |
| Ukraine | 1,250 | growing |
| Germany | 1,120 | flat |
| Turkey | 1,040 | flat |
| Netherlands | 1,010 | growing |
| Thailand | 900 | declining |
| South Korea | 840 | declining |
| Belarus | 780 | growing |

> Full per-country breakdown (59 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/wild-west-gold-b7/
- **Public page:** https://i-gaming.tools/slot-games/wild-west-gold-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
