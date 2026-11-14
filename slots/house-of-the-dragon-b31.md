# House of The Dragon

**Provider:** Blueprint Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/house-of-the-dragon-b31/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/house-of-the-dragon-b31/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/house-of-the-dragon-b31/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/house-of-the-dragon-b31/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/house-of-the-dragon-b31/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "house-of-the-dragon-b31",
  "name": "House of The Dragon",
  "status": "active",
  "provider": {
    "slug": "blueprint-gaming",
    "name": "Blueprint Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "94.00",
  "rtp_variants": [
    {
      "rtp": "94.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "94.00",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "93.00",
      "variant": "operator_config",
      "is_default": false
    }
  ],
  "volatility": "med_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-09-24",
  "themes": [
    {
      "slug": "dragons",
      "name": "Dragons"
    },
    {
      "slug": "fantasy",
      "name": "Fantasy"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/house-of-the-dragon-b31/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/house-of-the-dragon-b31/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/house-of-the-dragon-b31/demand/
```

**12-month volume (illustrative):** 1,460 · **trend:** growing · YoY +186.3%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Germany | 1,100 | declining |
| Brazil | 170 | declining |
| Austria | 100 | flat |
| Switzerland | 50 | declining |
| Portugal | 40 | flat |

> Full per-country breakdown (5 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/house-of-the-dragon-b31/
- **Public page:** https://i-gaming.tools/slot-games/house-of-the-dragon-b31/
- **Full schema:** https://i-gaming.tools/api/docs/
