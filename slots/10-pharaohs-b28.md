# 10 Pharaohs

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/10-pharaohs-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/10-pharaohs-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/10-pharaohs-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/10-pharaohs-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/10-pharaohs-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "10-pharaohs-b28",
  "name": "10 Pharaohs",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.26",
  "rtp_variants": [
    {
      "rtp": "96.26",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.28",
      "variant": "bonus_buy",
      "is_default": false
    },
    {
      "rtp": "96.46",
      "variant": "player_config",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "lines",
  "reels": 5,
  "rows": null,
  "jackpot_type": "fixed",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Random Free Spins",
      "cost": "75.00",
      "is_default": true
    }
  ],
  "release_date": "2025-04-09",
  "themes": [
    {
      "slug": "adventure",
      "name": "Adventure"
    },
    {
      "slug": "egyptian",
      "name": "Egyptian"
    },
    {
      "slug": "treasure",
      "name": "Treasure"
    }
  ],
  "features": [
    {
      "slug": "adjustable-grid",
      "name": "Adjustable Grid"
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
      "page_url": "https://i-gaming.tools/slot-games/10-pharaohs-b28/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/10-pharaohs-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/10-pharaohs-b28/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/10-pharaohs-b28/
- **Public page:** https://i-gaming.tools/slot-games/10-pharaohs-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
