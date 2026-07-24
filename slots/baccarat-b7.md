# Baccarat

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/baccarat-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/baccarat-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/baccarat-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/baccarat-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/baccarat-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "baccarat-b7",
  "name": "Baccarat",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "table",
  "rtp_default": "98.76",
  "rtp_variants": [
    {
      "rtp": "98.76",
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
  "release_date": null,
  "themes": [],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/baccarat-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/baccarat-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/baccarat-b7/demand/
```

**12-month volume (illustrative):** 37,660 · **trend:** flat · YoY -3.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Indonesia | 9,460 | flat |
| Philippines | 5,410 | declining |
| Brazil | 4,750 | growing |
| Thailand | 2,500 | flat |
| United States | 1,980 | flat |
| Malaysia | 1,400 | flat |
| Canada | 1,140 | growing |
| Vietnam | 920 | declining |
| Italy | 810 | growing |
| India | 760 | declining |

> Full per-country breakdown (60 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/baccarat-b7/
- **Public page:** https://i-gaming.tools/slot-games/baccarat-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
