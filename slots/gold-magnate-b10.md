# Gold Magnate

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/gold-magnate-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gold-magnate-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/gold-magnate-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/gold-magnate-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/gold-magnate-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "gold-magnate-b10",
  "name": "Gold Magnate",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.10",
  "rtp_variants": [
    {
      "rtp": "96.10",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.06",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Bonus Game",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2024-07-16",
  "themes": [
    {
      "slug": "cards",
      "name": "Cards"
    },
    {
      "slug": "dice",
      "name": "Dice"
    },
    {
      "slug": "victorian",
      "name": "Victorian"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "scatter",
      "name": "Scatter"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/gold-magnate-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/gold-magnate-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/gold-magnate-b10/demand/
```

**12-month volume (illustrative):** 430 · **trend:** growing · YoY +43.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 110 | declining |
| Finland | 40 | flat |
| Germany | 40 | flat |
| United Kingdom | 40 | flat |
| Poland | 30 | flat |
| Hungary | 20 | flat |
| India | 20 | flat |
| Indonesia | 20 | growing |
| Ukraine | 20 | flat |
| United States | 20 | flat |

> Full per-country breakdown (17 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/gold-magnate-b10/
- **Public page:** https://i-gaming.tools/slot-games/gold-magnate-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
