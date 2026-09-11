# Christmas Gift Rush

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/christmas-gift-rush-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/christmas-gift-rush-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/christmas-gift-rush-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/christmas-gift-rush-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/christmas-gift-rush-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "christmas-gift-rush-b29",
  "name": "Christmas Gift Rush",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.68",
  "rtp_variants": [
    {
      "rtp": "96.68",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.27",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "progressive",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Feature",
      "cost": "30.00",
      "is_default": true
    }
  ],
  "release_date": "2020-11-24",
  "themes": [
    {
      "slug": "christmas",
      "name": "Christmas"
    },
    {
      "slug": "toys",
      "name": "Toys"
    },
    {
      "slug": "winter",
      "name": "Winter"
    }
  ],
  "features": [
    {
      "slug": "expanding-paylines",
      "name": "Expanding Paylines"
    },
    {
      "slug": "nudge",
      "name": "Nudge"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/christmas-gift-rush-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/christmas-gift-rush-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/christmas-gift-rush-b29/demand/
```

**12-month volume (illustrative):** 3,320 · **trend:** declining · YoY -32.2%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 2,930 | growing |
| India | 60 | flat |
| Brazil | 30 | flat |
| El Salvador | 30 | flat |
| Canada | 20 | flat |
| Denmark | 20 | flat |
| Finland | 20 | flat |
| Germany | 20 | flat |
| Portugal | 20 | flat |
| United Kingdom | 20 | flat |

> Full per-country breakdown (24 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/christmas-gift-rush-b29/
- **Public page:** https://i-gaming.tools/slot-games/christmas-gift-rush-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
