# Chicken Road 2\.0

**Provider:** InOut Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/chicken-road-2-0-b22/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chicken-road-2-0-b22/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/chicken-road-2-0-b22/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/chicken-road-2-0-b22/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/chicken-road-2-0-b22/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "chicken-road-2-0-b22",
  "name": "Chicken Road 2.0",
  "status": "active",
  "provider": {
    "slug": "inout-games",
    "name": "InOut Games"
  },
  "game_category": "crash",
  "rtp_default": "95.50",
  "rtp_variants": [
    {
      "rtp": "95.50",
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
  "release_date": "2025-04-15",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "birds",
      "name": "Birds"
    }
  ],
  "features": [
    {
      "slug": "cash-out",
      "name": "Cash Out"
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
      "page_url": "https://i-gaming.tools/slot-games/chicken-road-2-0-b22/"
    }
  },
  "series": {
    "slug": "chicken-road",
    "name": "Chicken Road"
  }
}
```

## Search Demand

`GET /api/v1/slots/chicken-road-2-0-b22/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chicken-road-2-0-b22/demand/
```

**12-month volume (illustrative):** 139,860 · **trend:** growing · YoY +562.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 67,080 | declining |
| Pakistan | 16,860 | growing |
| Germany | 10,370 | declining |
| Italy | 9,850 | declining |
| Hungary | 3,460 | declining |
| Poland | 3,190 | declining |
| Romania | 2,510 | declining |
| Spain | 2,300 | declining |
| Greece | 2,180 | flat |
| Belgium | 1,940 | flat |

> Full per-country breakdown (78 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/chicken-road-2-0-b22/
- **Public page:** https://i-gaming.tools/slot-games/chicken-road-2-0-b22/
- **Full schema:** https://i-gaming.tools/api/docs/
