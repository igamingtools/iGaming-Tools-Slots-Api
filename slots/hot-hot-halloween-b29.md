# Hot Hot Halloween

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/hot-hot-halloween-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hot-hot-halloween-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/hot-hot-halloween-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/hot-hot-halloween-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/hot-hot-halloween-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "hot-hot-halloween-b29",
  "name": "Hot Hot Halloween",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.66",
  "rtp_variants": [
    {
      "rtp": "96.66",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "very_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2019-10-01",
  "themes": [
    {
      "slug": "halloween",
      "name": "Halloween"
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
      "slug": "splitting-symbols",
      "name": "Splitting Symbols"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/hot-hot-halloween-b29/"
    }
  },
  "series": {
    "slug": "hot-hot",
    "name": "Hot Hot"
  }
}
```

## Search Demand

`GET /api/v1/slots/hot-hot-halloween-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/hot-hot-halloween-b29/demand/
```

**12-month volume (illustrative):** 10,620 · **trend:** declining · YoY -15.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 9,410 | flat |
| India | 180 | growing |
| Tunisia | 130 | growing |
| Indonesia | 80 | declining |
| United States | 80 | flat |
| Italy | 60 | flat |
| Brazil | 50 | flat |
| Philippines | 50 | flat |
| United Kingdom | 50 | flat |
| Argentina | 40 | flat |

> Full per-country breakdown (40 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/hot-hot-halloween-b29/
- **Public page:** https://i-gaming.tools/slot-games/hot-hot-halloween-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
