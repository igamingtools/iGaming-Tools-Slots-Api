# The Dog House Megaways™

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/the-dog-house-megawaystm-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/the-dog-house-megawaystm-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/the-dog-house-megawaystm-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/the-dog-house-megawaystm-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/the-dog-house-megawaystm-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "the-dog-house-megawaystm-b7",
  "name": "The Dog House Megaways™",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.55",
  "rtp_variants": [
    {
      "rtp": "96.55",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "high",
  "mechanic": "megaways",
  "reels": 6,
  "rows": null,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2020-08-13",
  "themes": [
    {
      "slug": "dogs",
      "name": "Dogs"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "megaways",
      "name": "Megaways"
    },
    {
      "slug": "multiplier",
      "name": "Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/the-dog-house-megawaystm-b7/"
    }
  },
  "series": {
    "slug": "the-dog-house",
    "name": "The Dog House"
  }
}
```

## Search Demand

`GET /api/v1/slots/the-dog-house-megawaystm-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/the-dog-house-megawaystm-b7/demand/
```

**12-month volume (illustrative):** 21,860 · **trend:** declining · YoY -7.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| Greece | 4,650 | declining |
| Ukraine | 3,660 | growing |
| Switzerland | 990 | declining |
| Belarus | 930 | growing |
| Brazil | 800 | declining |
| United Kingdom | 700 | flat |
| Germany | 540 | declining |
| United States | 520 | flat |
| Latvia | 510 | declining |
| Italy | 490 | growing |

> Full per-country breakdown (60 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/the-dog-house-megawaystm-b7/
- **Public page:** https://i-gaming.tools/slot-games/the-dog-house-megawaystm-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
