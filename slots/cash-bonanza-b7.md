# Cash Bonanza

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/cash-bonanza-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/cash-bonanza-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/cash-bonanza-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/cash-bonanza-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/cash-bonanza-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "cash-bonanza-b7",
  "name": "Cash Bonanza",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.52",
  "rtp_variants": [
    {
      "rtp": "96.52",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "ways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2021-10-01",
  "themes": [
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "luxury",
      "name": "Luxury"
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
      "page_url": "https://i-gaming.tools/slot-games/cash-bonanza-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/cash-bonanza-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/cash-bonanza-b7/demand/
```

**12-month volume (illustrative):** 1,680 · **trend:** declining · YoY -34.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Latvia | 130 | flat |
| Brazil | 120 | declining |
| Canada | 100 | flat |
| Italy | 90 | flat |
| Finland | 80 | flat |
| Germany | 80 | flat |
| Greece | 80 | declining |
| Indonesia | 70 | flat |
| Mexico | 70 | declining |
| Argentina | 60 | flat |

> Full per-country breakdown (42 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/cash-bonanza-b7/
- **Public page:** https://i-gaming.tools/slot-games/cash-bonanza-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
