# OOF The Goldmine Planet

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/oof-the-goldmine-planet-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/oof-the-goldmine-planet-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/oof-the-goldmine-planet-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/oof-the-goldmine-planet-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/oof-the-goldmine-planet-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "oof-the-goldmine-planet-b10",
  "name": "OOF The Goldmine Planet",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "97.00",
  "rtp_variants": [
    {
      "rtp": "97.00",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "97.00",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "med_low",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Buy Bonus",
      "cost": "87.00",
      "is_default": true
    }
  ],
  "release_date": "2024-05-02",
  "themes": [
    {
      "slug": "mining",
      "name": "Mining"
    },
    {
      "slug": "space",
      "name": "Space"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "retrigger",
      "name": "Retrigger"
    },
    {
      "slug": "sticky-wins",
      "name": "Sticky Wins"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/oof-the-goldmine-planet-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/oof-the-goldmine-planet-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/oof-the-goldmine-planet-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/oof-the-goldmine-planet-b10/
- **Public page:** https://i-gaming.tools/slot-games/oof-the-goldmine-planet-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
