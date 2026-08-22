# Space XY

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/space-xy-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/space-xy-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/space-xy-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/space-xy-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/space-xy-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "space-xy-b10",
  "name": "Space XY",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "crash",
  "rtp_default": "96.88",
  "rtp_variants": [
    {
      "rtp": "96.88",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "98.92",
      "variant": "player_config",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2022-01-13",
  "themes": [
    {
      "slug": "space",
      "name": "Space"
    }
  ],
  "features": [
    {
      "slug": "cash-out",
      "name": "Cash Out"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/space-xy-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/space-xy-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/space-xy-b10/demand/
```

**12-month volume (illustrative):** 2,340 · **trend:** declining · YoY -29.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 450 | flat |
| India | 360 | flat |
| United States | 220 | flat |
| Canada | 160 | flat |
| Indonesia | 110 | flat |
| Germany | 80 | flat |
| Ukraine | 80 | declining |
| Pakistan | 60 | flat |
| Switzerland | 60 | growing |
| Portugal | 50 | flat |

> Full per-country breakdown (44 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/space-xy-b10/
- **Public page:** https://i-gaming.tools/slot-games/space-xy-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
