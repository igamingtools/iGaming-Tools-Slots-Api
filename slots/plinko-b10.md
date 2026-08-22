# Plinko

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/plinko-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/plinko-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/plinko-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/plinko-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/plinko-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "plinko-b10",
  "name": "Plinko",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "crash",
  "rtp_default": "98.91",
  "rtp_variants": [
    {
      "rtp": "98.91",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "99.16",
      "variant": "player_config",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2019-01-28",
  "themes": [],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/plinko-b10/"
    }
  },
  "series": {
    "slug": "plinko",
    "name": "Plinko"
  }
}
```

## Search Demand

`GET /api/v1/slots/plinko-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/plinko-b10/demand/
```

**12-month volume (illustrative):** 82,720 · **trend:** declining · YoY -67.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Indonesia | 8,820 | declining |
| United States | 6,420 | declining |
| Italy | 5,660 | flat |
| India | 5,280 | declining |
| Germany | 4,410 | declining |
| United Kingdom | 3,510 | declining |
| Switzerland | 2,560 | declining |
| Canada | 2,540 | declining |
| Romania | 2,340 | declining |
| South Africa | 2,320 | declining |

> Full per-country breakdown (80 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/plinko-b10/
- **Public page:** https://i-gaming.tools/slot-games/plinko-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
