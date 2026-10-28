# Spirited Wonders

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/spirited-wonders-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/spirited-wonders-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/spirited-wonders-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/spirited-wonders-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/spirited-wonders-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "spirited-wonders-b30",
  "name": "Spirited Wonders",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.70",
  "rtp_variants": [
    {
      "rtp": "96.70",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "variable_ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2021-11-01",
  "themes": [
    {
      "slug": "ghosts",
      "name": "Ghosts"
    },
    {
      "slug": "japanese",
      "name": "Japanese"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "mystery_symbol",
      "name": "Mystery Symbol"
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
      "page_url": "https://i-gaming.tools/slot-games/spirited-wonders-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/spirited-wonders-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/spirited-wonders-b30/demand/
```

**12-month volume (illustrative):** 2,250 · **trend:** declining · YoY -36.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 490 | declining |
| Indonesia | 300 | flat |
| India | 260 | flat |
| Pakistan | 180 | growing |
| Philippines | 140 | flat |
| Tunisia | 110 | declining |
| Turkey | 100 | declining |
| Thailand | 90 | growing |
| Germany | 70 | flat |
| United Kingdom | 60 | flat |

> Full per-country breakdown (32 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/spirited-wonders-b30/
- **Public page:** https://i-gaming.tools/slot-games/spirited-wonders-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
