# Panda's Fortune

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/panda-s-fortune-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/panda-s-fortune-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/panda-s-fortune-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/panda-s-fortune-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/panda-s-fortune-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "panda-s-fortune-b7",
  "name": "Panda's Fortune",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.17",
  "rtp_variants": [
    {
      "rtp": "96.17",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2017-11-01",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "panda",
      "name": "Panda"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "gold-symbols",
      "name": "Gold Symbols"
    },
    {
      "slug": "mystery_symbol",
      "name": "Mystery Symbol"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/panda-s-fortune-b7/"
    }
  },
  "series": {
    "slug": "pandas-fortune",
    "name": "Panda's Fortune"
  }
}
```

## Search Demand

`GET /api/v1/slots/panda-s-fortune-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/panda-s-fortune-b7/demand/
```

**12-month volume (illustrative):** 510 · **trend:** declining · YoY -17.7%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 80 | declining |
| Australia | 60 | declining |
| Greece | 50 | growing |
| Argentina | 40 | flat |
| Mexico | 30 | flat |
| Philippines | 30 | flat |
| Canada | 20 | flat |
| Germany | 20 | flat |
| India | 20 | flat |
| Turkey | 20 | flat |

> Full per-country breakdown (22 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/panda-s-fortune-b7/
- **Public page:** https://i-gaming.tools/slot-games/panda-s-fortune-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
