# Geisha's Revenge

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/geisha-s-revenge-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/geisha-s-revenge-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/geisha-s-revenge-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/geisha-s-revenge-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/geisha-s-revenge-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "geisha-s-revenge-b30",
  "name": "Geisha's Revenge",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.78",
  "rtp_variants": [
    {
      "rtp": "96.78",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "variable_ways",
  "reels": 5,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-12-01",
  "themes": [
    {
      "slug": "japanese",
      "name": "Japanese"
    },
    {
      "slug": "winter",
      "name": "Winter"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "giant-symbol",
      "name": "Giant Symbol"
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
      "page_url": "https://i-gaming.tools/slot-games/geisha-s-revenge-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/geisha-s-revenge-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/geisha-s-revenge-b30/demand/
```

**12-month volume (illustrative):** 3,460 · **trend:** growing · YoY +90.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Philippines | 2,120 | declining |
| Brazil | 400 | declining |
| India | 200 | flat |
| Pakistan | 140 | flat |
| Indonesia | 90 | flat |
| United States | 80 | growing |
| Canada | 60 | flat |
| Greece | 60 | declining |
| Tunisia | 40 | flat |
| Mexico | 30 | flat |

> Full per-country breakdown (28 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/geisha-s-revenge-b30/
- **Public page:** https://i-gaming.tools/slot-games/geisha-s-revenge-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
