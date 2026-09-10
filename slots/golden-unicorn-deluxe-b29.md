# Golden Unicorn Deluxe

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/golden-unicorn-deluxe-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/golden-unicorn-deluxe-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/golden-unicorn-deluxe-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/golden-unicorn-deluxe-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/golden-unicorn-deluxe-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "golden-unicorn-deluxe-b29",
  "name": "Golden Unicorn Deluxe",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.80",
  "rtp_variants": [
    {
      "rtp": "96.80",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.72",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.68",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "progressive",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Games (Palace)",
      "cost": "40.80",
      "is_default": true
    },
    {
      "label": "Chest Feature",
      "cost": "15.04",
      "is_default": false
    }
  ],
  "release_date": "2022-06-28",
  "themes": [
    {
      "slug": "fairy-tale",
      "name": "Fairy Tale"
    },
    {
      "slug": "fantasy",
      "name": "Fantasy"
    },
    {
      "slug": "forest",
      "name": "Forest"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "nudge",
      "name": "Nudge"
    },
    {
      "slug": "pick_bonus",
      "name": "Pick Bonus"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/golden-unicorn-deluxe-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/golden-unicorn-deluxe-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/golden-unicorn-deluxe-b29/demand/
```

**12-month volume (illustrative):** 2,370 · **trend:** declining · YoY -44.5%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 1,950 | declining |
| Norway | 40 | flat |
| Italy | 30 | flat |
| Mexico | 30 | growing |
| Philippines | 30 | flat |
| Australia | 20 | flat |
| Canada | 20 | flat |
| El Salvador | 20 | flat |
| India | 20 | flat |
| Lithuania | 20 | flat |

> Full per-country breakdown (25 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/golden-unicorn-deluxe-b29/
- **Public page:** https://i-gaming.tools/slot-games/golden-unicorn-deluxe-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
