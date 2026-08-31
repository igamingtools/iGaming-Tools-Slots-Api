# Cats of Olympuss

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/cats-of-olympuss-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/cats-of-olympuss-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/cats-of-olympuss-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/cats-of-olympuss-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/cats-of-olympuss-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "cats-of-olympuss-b28",
  "name": "Cats of Olympuss",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.31",
  "rtp_variants": [
    {
      "rtp": "96.31",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.26",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.24",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "ways",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "3 Bonus Symbols Free Spins",
      "cost": "60.30",
      "is_default": true
    },
    {
      "label": "4 Bonus Symbols Free Spins",
      "cost": "110.00",
      "is_default": false
    }
  ],
  "release_date": "2024-09-12",
  "themes": [
    {
      "slug": "ancient-greece",
      "name": "Ancient Greece"
    },
    {
      "slug": "cats",
      "name": "Cats"
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
      "slug": "growing-reels",
      "name": "Growing Reels"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/cats-of-olympuss-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/cats-of-olympuss-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/cats-of-olympuss-b28/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/cats-of-olympuss-b28/
- **Public page:** https://i-gaming.tools/slot-games/cats-of-olympuss-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
