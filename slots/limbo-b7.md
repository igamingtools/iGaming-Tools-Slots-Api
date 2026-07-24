# Limbo\+

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/limbo-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/limbo-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/limbo-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/limbo-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/limbo-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "limbo-b7",
  "name": "Limbo+",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "crash",
  "rtp_default": "97.50",
  "rtp_variants": [
    {
      "rtp": "97.50",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-04-23",
  "themes": [],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/limbo-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/limbo-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/limbo-b7/demand/
```

**12-month volume (illustrative):** 18,090 · **trend:** declining · YoY -62.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 8,300 | flat |
| Brazil | 1,230 | declining |
| United States | 1,000 | declining |
| Canada | 520 | declining |
| Indonesia | 420 | flat |
| Germany | 340 | declining |
| Mexico | 290 | declining |
| Philippines | 290 | declining |
| Malaysia | 240 | flat |
| Belgium | 220 | declining |

> Full per-country breakdown (63 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/limbo-b7/
- **Public page:** https://i-gaming.tools/slot-games/limbo-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
