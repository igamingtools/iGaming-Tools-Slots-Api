# Futebol Fever

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/futebol-fever-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/futebol-fever-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/futebol-fever-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/futebol-fever-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/futebol-fever-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "futebol-fever-b30",
  "name": "Futebol Fever",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.75",
  "rtp_variants": [
    {
      "rtp": "96.75",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "ways",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-07-01",
  "themes": [
    {
      "slug": "brazilian",
      "name": "Brazilian"
    },
    {
      "slug": "sports",
      "name": "Sports"
    },
    {
      "slug": "urban",
      "name": "Urban"
    }
  ],
  "features": [
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "respin",
      "name": "Respin"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/futebol-fever-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/futebol-fever-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/futebol-fever-b30/demand/
```

**12-month volume (illustrative):** 5,700 · **trend:** declining · YoY -68.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 4,540 | declining |
| India | 160 | flat |
| Indonesia | 120 | flat |
| Philippines | 120 | growing |
| Greece | 80 | declining |
| Pakistan | 60 | declining |
| Tunisia | 50 | flat |
| Canada | 40 | flat |
| Thailand | 40 | flat |
| Germany | 30 | flat |

> Full per-country breakdown (37 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/futebol-fever-b30/
- **Public page:** https://i-gaming.tools/slot-games/futebol-fever-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
