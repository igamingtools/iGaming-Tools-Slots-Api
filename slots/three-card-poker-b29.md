# Three Card Poker

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/three-card-poker-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/three-card-poker-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/three-card-poker-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/three-card-poker-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/three-card-poker-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "three-card-poker-b29",
  "name": "Three Card Poker",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "table",
  "rtp_default": "97.99",
  "rtp_variants": [
    {
      "rtp": "97.99",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.68",
      "variant": "player_config",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "unknown",
  "bonus_buys": [],
  "release_date": null,
  "themes": [],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/three-card-poker-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/three-card-poker-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/three-card-poker-b29/demand/
```

**12-month volume (illustrative):** 1,990 · **trend:** growing · YoY +16.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United Kingdom | 370 | declining |
| United States | 240 | flat |
| Canada | 220 | growing |
| Finland | 100 | flat |
| Netherlands | 100 | flat |
| Belgium | 80 | declining |
| Sweden | 80 | flat |
| Italy | 70 | flat |
| India | 60 | flat |
| Indonesia | 60 | declining |

> Full per-country breakdown (40 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/three-card-poker-b29/
- **Public page:** https://i-gaming.tools/slot-games/three-card-poker-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
