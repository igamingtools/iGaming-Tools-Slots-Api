# Slime Party

**Provider:** Habanero

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/slime-party-b29/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/slime-party-b29/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/slime-party-b29/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/slime-party-b29/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/slime-party-b29/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "slime-party-b29",
  "name": "Slime Party",
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
    },
    {
      "rtp": "96.64",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.88",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "very_high",
  "mechanic": "scatter_pays",
  "reels": 5,
  "rows": 4,
  "jackpot_type": "progressive",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Feature",
      "cost": "49.95",
      "is_default": true
    }
  ],
  "release_date": "2023-10-17",
  "themes": [
    {
      "slug": "sweets",
      "name": "Sweets"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "progressive_multiplier",
      "name": "Progressive Multiplier"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/slime-party-b29/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/slime-party-b29/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/slime-party-b29/demand/
```

**12-month volume (illustrative):** 9,710 · **trend:** declining · YoY -48.0%

> Illustrative snapshot — query the live endpoint for current values.

| Country | 12-month volume | Trend |
|---|---|---|
| South Africa | 8,540 | growing |
| India | 140 | flat |
| Tunisia | 70 | flat |
| Ukraine | 70 | declining |
| Canada | 60 | declining |
| United States | 60 | flat |
| Indonesia | 50 | growing |
| Italy | 50 | growing |
| Philippines | 50 | growing |
| United Kingdom | 50 | flat |

> Full per-country breakdown (41 markets) via the /demand/ endpoint.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/slime-party-b29/
- **Public page:** https://i-gaming.tools/slot-games/slime-party-b29/
- **Full schema:** https://i-gaming.tools/api/docs/
