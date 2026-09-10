# Mount Mazuma

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/mount-mazuma-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mount-mazuma-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/mount-mazuma-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/mount-mazuma-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/mount-mazuma-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "mount-mazuma-b29",
  "name": "Mount Mazuma",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.73",
  "rtp_variants": [
    {
      "rtp": "96.73",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "very_high",
  "mechanic": "variable_ways",
  "reels": 5,
  "rows": null,
  "jackpot_type": "progressive",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2019-03-26",
  "themes": [
    {
      "slug": "fruits",
      "name": "Fruits"
    },
    {
      "slug": "tropical",
      "name": "Tropical"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "growing-reels",
      "name": "Growing Reels"
    },
    {
      "slug": "guaranteed-win",
      "name": "Guaranteed Win"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/mount-mazuma-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/mount-mazuma-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/mount-mazuma-b29/demand/
```

**12-month volume (illustrative):** 1,480 · **trend:** declining · YoY -32.1%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 1,100 | declining |
| India | 80 | flat |
| Tunisia | 60 | flat |
| Australia | 50 | flat |
| Indonesia | 50 | flat |
| Mexico | 40 | declining |
| United States | 20 | flat |
| Brazil | 10 | flat |
| Chile | 10 | growing |
| Colombia | 10 | flat |

> Full per-country breakdown (15 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/mount-mazuma-b29/
- **Public page:** https://i-gaming.tools/slot-games/mount-mazuma-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
