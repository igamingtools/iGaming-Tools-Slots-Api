# Aviamasters

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/aviamasters-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/aviamasters-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/aviamasters-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/aviamasters-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/aviamasters-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "aviamasters-b10",
  "name": "Aviamasters",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "crash",
  "rtp_default": "97.00",
  "rtp_variants": [
    {
      "rtp": "97.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "low",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-07-02",
  "themes": [
    {
      "slug": "aviation",
      "name": "Aviation"
    }
  ],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/aviamasters-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/aviamasters-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/aviamasters-b10/demand/
```

**12-month volume (illustrative):** 11,200 · **trend:** growing · YoY +97.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| United States | 2,420 | declining |
| Canada | 1,100 | growing |
| United Kingdom | 970 | growing |
| Finland | 700 | flat |
| Germany | 630 | growing |
| Australia | 370 | flat |
| Poland | 340 | growing |
| Turkey | 340 | flat |
| Greece | 330 | declining |
| Switzerland | 330 | growing |

> Full per-country breakdown (33 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/aviamasters-b10/
- **Public page:** https://i-gaming.tools/slot-games/aviamasters-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
