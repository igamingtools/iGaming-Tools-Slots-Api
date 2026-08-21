# Fortune Trio: Minions Of Fu

**Provider:** BGaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/fortune-trio-minions-of-fu-b10/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fortune-trio-minions-of-fu-b10/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/fortune-trio-minions-of-fu-b10/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/fortune-trio-minions-of-fu-b10/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/fortune-trio-minions-of-fu-b10/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "fortune-trio-minions-of-fu-b10",
  "name": "Fortune Trio: Minions Of Fu",
  "status": "active",
  "provider": {
    "slug": "bgaming",
    "name": "BGaming"
  },
  "game_category": "video_slot",
  "rtp_default": "95.05",
  "rtp_variants": [
    {
      "rtp": "95.05",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "95.25",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "95.25",
      "variant": "bonus_buy",
      "is_default": false
    }
  ],
  "volatility": "",
  "mechanic": "lines",
  "reels": 5,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Giant Symbol (Free Spins)",
      "cost": "48.00",
      "is_default": true
    },
    {
      "label": "Hold & Win",
      "cost": "40.00",
      "is_default": false
    }
  ],
  "release_date": "2026-08-27",
  "themes": [
    {
      "slug": "chinese",
      "name": "Chinese"
    },
    {
      "slug": "mythology",
      "name": "Mythology"
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
      "slug": "giant-symbol",
      "name": "Giant Symbol"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/fortune-trio-minions-of-fu-b10/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/fortune-trio-minions-of-fu-b10/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/fortune-trio-minions-of-fu-b10/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/fortune-trio-minions-of-fu-b10/
- **Public page:** https://i-gaming.tools/slot-games/fortune-trio-minions-of-fu-b10/
- **Full schema:** https://i-gaming.tools/api/docs/
