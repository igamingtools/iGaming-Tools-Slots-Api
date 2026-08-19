# Chicken Road

**Provider:** InOut Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/chicken-road-b22/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chicken-road-b22/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/chicken-road-b22/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/chicken-road-b22/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/chicken-road-b22/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "chicken-road-b22",
  "name": "Chicken Road",
  "status": "active",
  "provider": {
    "slug": "inout-games",
    "name": "InOut Games"
  },
  "game_category": "crash",
  "rtp_default": "98.00",
  "rtp_variants": [
    {
      "rtp": "98.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "unknown",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-04-04",
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
      "page_url": "https://i-gaming.tools/slot-games/chicken-road-b22/"
    }
  },
  "series": {
    "slug": "chicken-road",
    "name": "Chicken Road"
  }
}
```

## Search Demand

`GET /api/v1/slots/chicken-road-b22/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chicken-road-b22/demand/
```

**12-month volume (illustrative):** 274,150 · **trend:** growing · YoY +193.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| India | 142,000 | flat |
| Italy | 17,230 | declining |
| Pakistan | 16,800 | growing |
| Germany | 15,780 | declining |
| France | 9,800 | growing |
| Greece | 6,110 | declining |
| Spain | 5,040 | declining |
| Poland | 4,690 | declining |
| Romania | 4,340 | declining |
| United Kingdom | 3,770 | growing |

> Full per-country breakdown (80 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/chicken-road-b22/
- **Public page:** https://i-gaming.tools/slot-games/chicken-road-b22/
- **Full schema:** https://i-gaming.tools/api/docs/
