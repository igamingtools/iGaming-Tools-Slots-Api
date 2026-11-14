# Cash Strike Hotstepper 2

**Provider:** Blueprint Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/cash-strike-hotstepper-2-b31/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/cash-strike-hotstepper-2-b31/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/cash-strike-hotstepper-2-b31/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/cash-strike-hotstepper-2-b31/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/cash-strike-hotstepper-2-b31/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "cash-strike-hotstepper-2-b31",
  "name": "Cash Strike Hotstepper 2",
  "status": "active",
  "provider": {
    "slug": "blueprint-gaming",
    "name": "Blueprint Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "95.00",
  "rtp_variants": [
    {
      "rtp": "95.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "95.00",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "92.00",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "med_high",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2025-09-11",
  "themes": [
    {
      "slug": "classic",
      "name": "Classic"
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
      "page_url": "https://i-gaming.tools/slot-games/cash-strike-hotstepper-2-b31/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/cash-strike-hotstepper-2-b31/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/cash-strike-hotstepper-2-b31/demand/
```

**12-month volume (illustrative):** 2,710 · **trend:** growing · YoY +942.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 750 | growing |
| Canada | 680 | flat |
| Netherlands | 220 | flat |
| United States | 140 | growing |
| Ireland | 90 | flat |
| Italy | 80 | flat |
| Greece | 60 | flat |
| Portugal | 60 | declining |
| South Africa | 60 | flat |
| Sweden | 60 | flat |

> Full per-country breakdown (35 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/cash-strike-hotstepper-2-b31/
- **Public page:** https://i-gaming.tools/slot-games/cash-strike-hotstepper-2-b31/
- **Full schema:** https://i-gaming.tools/api/docs/
