# Gold Party 2 – After Hours

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/gold-party-2-after-hours-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gold-party-2-after-hours-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/gold-party-2-after-hours-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/gold-party-2-after-hours-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/gold-party-2-after-hours-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "gold-party-2-after-hours-b7",
  "name": "Gold Party 2 – After Hours",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.50",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Money Respin",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2025-06-26",
  "themes": [
    {
      "slug": "irish",
      "name": "Irish"
    },
    {
      "slug": "luxury",
      "name": "Luxury"
    },
    {
      "slug": "party",
      "name": "Party"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/gold-party-2-after-hours-b7/"
    }
  },
  "series": {
    "slug": "gold-party",
    "name": "Gold Party"
  }
}
```

## Search Demand

`GET /api/v1/slots/gold-party-2-after-hours-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gold-party-2-after-hours-b7/demand/
```

**12-month volume (illustrative):** 2,400 · **trend:** growing · YoY +500.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Portugal | 390 | flat |
| Argentina | 130 | declining |
| Germany | 130 | flat |
| Switzerland | 120 | flat |
| United States | 120 | flat |
| Greece | 110 | declining |
| Turkey | 100 | declining |
| Brazil | 90 | declining |
| Finland | 80 | declining |
| United Kingdom | 80 | flat |

> Full per-country breakdown (45 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/gold-party-2-after-hours-b7/
- **Public page:** https://i-gaming.tools/slot-games/gold-party-2-after-hours-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
