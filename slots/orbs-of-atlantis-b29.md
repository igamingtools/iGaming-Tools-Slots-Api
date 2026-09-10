# Orbs of Atlantis

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/orbs-of-atlantis-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/orbs-of-atlantis-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/orbs-of-atlantis-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/orbs-of-atlantis-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/orbs-of-atlantis-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "orbs-of-atlantis-b29",
  "name": "Orbs of Atlantis",
  "status": "active",
  "provider": {
    "slug": "habanero",
    "name": "Habanero"
  },
  "game_category": "video_slot",
  "rtp_default": "96.58",
  "rtp_variants": [
    {
      "rtp": "96.58",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.67",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.77",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "progressive",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "3-8 Scatters (10-500 Free Games)",
      "cost": "30.00",
      "is_default": true
    },
    {
      "label": "4 Scatters (25 Free Games)",
      "cost": "43.33",
      "is_default": false
    }
  ],
  "release_date": "2021-02-23",
  "themes": [
    {
      "slug": "mythology",
      "name": "Mythology"
    },
    {
      "slug": "ocean",
      "name": "Ocean"
    },
    {
      "slug": "treasure",
      "name": "Treasure"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
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
      "page_url": "https://i-gaming.tools/slot-games/orbs-of-atlantis-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/orbs-of-atlantis-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/orbs-of-atlantis-b29/demand/
```

**12-month volume (illustrative):** 2,100 · **trend:** declining · YoY -14.6%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 1,430 | declining |
| Mexico | 180 | flat |
| Tunisia | 110 | flat |
| India | 100 | flat |
| Malaysia | 60 | flat |
| Norway | 50 | flat |
| United States | 40 | flat |
| Indonesia | 20 | flat |
| Pakistan | 20 | flat |
| Australia | 10 | flat |

> Full per-country breakdown (18 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/orbs-of-atlantis-b29/
- **Public page:** https://i-gaming.tools/slot-games/orbs-of-atlantis-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
