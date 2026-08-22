# Fishing Club

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fishing-club-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fishing-club-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fishing-club-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fishing-club-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fishing-club-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fishing-club-b10",
  "name": "Fishing Club",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "instant_win",
  "rtp_default": "97.16",
  "rtp_variants": [
    {
      "rtp": "97.16",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.15",
      "variant": "default",
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
  "release_date": "2024-06-11",
  "themes": [
    {
      "slug": "fishing",
      "name": "Fishing"
    }
  ],
  "features": [],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/fishing-club-b10/"
    }
  },
  "series": {
    "slug": "fishing-club",
    "name": "Fishing Club"
  }
}
```

## Search Demand

`GET /api/v1/slots/fishing-club-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fishing-club-b10/demand/
```

**12-month volume (illustrative):** 2,670 · **trend:** growing · YoY +65.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 680 | declining |
| Brazil | 250 | growing |
| United Kingdom | 230 | declining |
| United States | 170 | flat |
| Germany | 120 | growing |
| Pakistan | 120 | flat |
| Netherlands | 80 | declining |
| Turkey | 80 | flat |
| Mexico | 60 | growing |
| Switzerland | 60 | flat |

> Full per-country breakdown (44 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fishing-club-b10/
- **Public page:** https://i-gaming.tools/slot-games/fishing-club-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
