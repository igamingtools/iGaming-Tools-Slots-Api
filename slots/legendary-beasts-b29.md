# Legendary Beasts

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/legendary-beasts-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/legendary-beasts-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/legendary-beasts-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/legendary-beasts-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/legendary-beasts-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "legendary-beasts-b29",
  "name": "Legendary Beasts",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.81",
  "rtp_variants": [
    {
      "rtp": "96.81",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "low",
  "mechanic": "variable_ways",
  "reels": 3,
  "rows": null,
  "jackpot_type": "progressive",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2023-03-28",
  "themes": [
    {
      "slug": "birds",
      "name": "Birds"
    },
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "dragons",
      "name": "Dragons"
    }
  ],
  "features": [
    {
      "slug": "multiplier",
      "name": "Multiplier"
    },
    {
      "slug": "splitting-symbols",
      "name": "Splitting Symbols"
    },
    {
      "slug": "wild",
      "name": "Wild"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/legendary-beasts-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/legendary-beasts-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/legendary-beasts-b29/demand/
```

**12-month volume (illustrative):** 3,920 · **trend:** declining · YoY -19.8%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 3,410 | declining |
| India | 60 | flat |
| Indonesia | 50 | growing |
| Italy | 50 | flat |
| Peru | 40 | flat |
| United States | 40 | flat |
| Tunisia | 30 | flat |
| Brazil | 20 | flat |
| Germany | 20 | flat |
| Lithuania | 20 | flat |

> Full per-country breakdown (24 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/legendary-beasts-b29/
- **Public page:** https://i-gaming.tools/slot-games/legendary-beasts-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
