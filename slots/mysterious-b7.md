# Mysterious

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mysterious-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mysterious-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mysterious-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mysterious-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mysterious-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mysterious-b7",
  "name": "Mysterious",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.50",
  "rtp_variants": [
    {
      "rtp": "96.50",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": null,
  "rows": 4,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2020-02-20",
  "themes": [
    {
      "slug": "horror",
      "name": "Horror"
    },
    {
      "slug": "victorian",
      "name": "Victorian"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "random-wilds",
      "name": "Random Wilds"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/mysterious-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/mysterious-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mysterious-b7/demand/
```

**12-month volume (illustrative):** 820 · **trend:** declining · YoY -21.9%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 120 | flat |
| Greece | 120 | flat |
| Finland | 60 | declining |
| United States | 60 | declining |
| Germany | 50 | flat |
| Indonesia | 50 | growing |
| Philippines | 40 | flat |
| Colombia | 30 | flat |
| Romania | 30 | flat |
| France | 20 | flat |

> Full per-country breakdown (29 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mysterious-b7/
- **Public page:** https://i-gaming.tools/slot-games/mysterious-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
