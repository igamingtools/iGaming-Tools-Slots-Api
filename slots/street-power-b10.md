# Street Power

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/street-power-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/street-power-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/street-power-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/street-power-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/street-power-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "street-power-b10",
  "name": "Street Power",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "instant_win",
  "rtp_default": "97.15",
  "rtp_variants": [
    {
      "rtp": "97.15",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-08-06",
  "themes": [
    {
      "slug": "superheroes",
      "name": "Superheroes"
    }
  ],
  "features": [
    {
      "slug": "guaranteed-win",
      "name": "Guaranteed Win"
    },
    {
      "slug": "variable_volatility",
      "name": "Variable Volatility"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/street-power-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/street-power-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/street-power-b10/demand/
```

**12-month volume (illustrative):** 110 · **trend:** declining · YoY -63.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 30 | flat |
| Australia | 20 | flat |
| United States | 20 | flat |
| Germany | 10 | growing |
| Italy | 10 | flat |
| Netherlands | 10 | flat |
| Portugal | 10 | flat |

> Full per-country breakdown (7 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/street-power-b10/
- **Public page:** https://i-gaming.tools/slot-games/street-power-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
