# Tramp Day TRUEWAYS™

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/tramp-day-truewaystm-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/tramp-day-truewaystm-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/tramp-day-truewaystm-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/tramp-day-truewaystm-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/tramp-day-truewaystm-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "tramp-day-truewaystm-b10",
  "name": "Tramp Day TRUEWAYS™",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.70",
  "rtp_variants": [
    {
      "rtp": "96.70",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Coin Respin",
      "cost": "100.00",
      "is_default": false
    }
  ],
  "release_date": "2025-07-10",
  "themes": [
    {
      "slug": "money",
      "name": "Money"
    },
    {
      "slug": "urban",
      "name": "Urban"
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
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/tramp-day-truewaystm-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/tramp-day-truewaystm-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/tramp-day-truewaystm-b10/demand/
```

**12-month volume (illustrative):** 400 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Finland | 60 | growing |
| United States | 60 | declining |
| Australia | 50 | flat |
| New Zealand | 30 | growing |
| United Kingdom | 30 | declining |
| Belgium | 20 | flat |
| Canada | 20 | flat |
| Denmark | 20 | growing |
| Greece | 20 | declining |
| Argentina | 10 | declining |

> Full per-country breakdown (16 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/tramp-day-truewaystm-b10/
- **Public page:** https://i-gaming.tools/slot-games/tramp-day-truewaystm-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
