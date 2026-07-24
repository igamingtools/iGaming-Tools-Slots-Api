# Fire Strike 2

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fire-strike-2-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fire-strike-2-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fire-strike-2-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fire-strike-2-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fire-strike-2-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fire-strike-2-b7",
  "name": "Fire Strike 2",
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
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2022-05-05",
  "themes": [
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
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
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
      "page_url": "https://i-gaming.tools/slot-games/fire-strike-2-b7/"
    }
  },
  "series": {
    "slug": "fire-strike",
    "name": "Fire Strike"
  }
}
```

## Search Demand

`GET /api/v1/slots/fire-strike-2-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fire-strike-2-b7/demand/
```

**12-month volume (illustrative):** 2,730 · **trend:** declining · YoY -21.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 940 | declining |
| United States | 200 | declining |
| Finland | 160 | declining |
| Argentina | 100 | declining |
| India | 100 | flat |
| United Kingdom | 100 | declining |
| Denmark | 90 | declining |
| Greece | 80 | declining |
| Malaysia | 80 | declining |
| Mexico | 80 | declining |

> Full per-country breakdown (41 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fire-strike-2-b7/
- **Public page:** https://i-gaming.tools/slot-games/fire-strike-2-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
