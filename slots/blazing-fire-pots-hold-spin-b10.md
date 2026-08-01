# Blazing Fire Pots Hold & Spin

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/blazing-fire-pots-hold-spin-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/blazing-fire-pots-hold-spin-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/blazing-fire-pots-hold-spin-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/blazing-fire-pots-hold-spin-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/blazing-fire-pots-hold-spin-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "blazing-fire-pots-hold-spin-b10",
  "name": "Blazing Fire Pots Hold & Spin",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.03",
  "rtp_variants": [
    {
      "rtp": "96.03",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "med_high",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Blazing Bonus",
      "cost": "100.00",
      "is_default": true
    }
  ],
  "release_date": "2026-01-21",
  "themes": [
    {
      "slug": "classic",
      "name": "Classic"
    },
    {
      "slug": "fire",
      "name": "Fire"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "hold-and-spin",
      "name": "Hold and Spin"
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
      "page_url": "https://i-gaming.tools/slot-games/blazing-fire-pots-hold-spin-b10/"
    }
  },
  "studio": {
    "slug": "electric-elephant-games",
    "name": "Electric Elephant Games"
  }
}
```

## Search Demand

`GET /api/v1/slots/blazing-fire-pots-hold-spin-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/blazing-fire-pots-hold-spin-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/blazing-fire-pots-hold-spin-b10/
- **Public page:** https://i-gaming.tools/slot-games/blazing-fire-pots-hold-spin-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
