# Three Crazy Piggies

**Provider:** Pocket Games Soft

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/three-crazy-piggies-b30/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/three-crazy-piggies-b30/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/three-crazy-piggies-b30/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/three-crazy-piggies-b30/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/three-crazy-piggies-b30/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "three-crazy-piggies-b30",
  "name": "Three Crazy Piggies",
  "status": "active",
  "provider": {
    "slug": "pocket-games-soft",
    "name": "Pocket Games Soft"
  },
  "game_category": "video_slot",
  "rtp_default": "96.72",
  "rtp_variants": [
    {
      "rtp": "96.72",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "medium",
  "mechanic": "ways",
  "reels": 5,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2024-09-01",
  "themes": [
    {
      "slug": "fairy-tale",
      "name": "Fairy Tale"
    },
    {
      "slug": "pigs",
      "name": "Pigs"
    },
    {
      "slug": "wolves",
      "name": "Wolves"
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
      "slug": "retrigger",
      "name": "Retrigger"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/three-crazy-piggies-b30/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/three-crazy-piggies-b30/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/three-crazy-piggies-b30/demand/
```

**12-month volume (illustrative):** 3,910 · **trend:** declining · YoY -52.4%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Brazil | 1,170 | flat |
| India | 1,060 | growing |
| Indonesia | 310 | growing |
| Pakistan | 280 | declining |
| Philippines | 170 | flat |
| Canada | 100 | flat |
| Thailand | 100 | flat |
| United States | 80 | flat |
| Mexico | 50 | flat |
| Tunisia | 50 | flat |

> Full per-country breakdown (39 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/three-crazy-piggies-b30/
- **Public page:** https://i-gaming.tools/slot-games/three-crazy-piggies-b30/
- **Full schema:** https://i-gaming.tools/api/docs/
