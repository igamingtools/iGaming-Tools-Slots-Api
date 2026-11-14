# Rat Royale

**Provider:** Pragmatic Play

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/rat-royale-b7/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rat-royale-b7/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/rat-royale-b7/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/rat-royale-b7/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/rat-royale-b7/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "rat-royale-b7",
  "name": "Rat Royale",
  "status": "active",
  "provider": {
    "slug": "pragmatic-play",
    "name": "Pragmatic Play"
  },
  "game_category": "video_slot",
  "rtp_default": "96.52",
  "rtp_variants": [
    {
      "rtp": "96.52",
      "variant": "default",
      "is_default": true
    },
    {
      "rtp": "96.54",
      "variant": "ante_bet",
      "is_default": false
    },
    {
      "rtp": "96.48",
      "variant": "ante_bet",
      "is_default": false
    }
  ],
  "volatility": "medium",
  "mechanic": "ways",
  "reels": 5,
  "rows": 5,
  "jackpot_type": "none",
  "has_bonus_buy": "yes",
  "bonus_buys": [
    {
      "label": "Free Spins",
      "cost": "100.00",
      "is_default": true
    },
    {
      "label": "Super Free Spins",
      "cost": "500.00",
      "is_default": false
    }
  ],
  "release_date": "2026-10-22",
  "themes": [
    {
      "slug": "animals",
      "name": "Animals"
    },
    {
      "slug": "fantasy",
      "name": "Fantasy"
    },
    {
      "slug": "medieval",
      "name": "Medieval"
    }
  ],
  "features": [
    {
      "slug": "ante_bet",
      "name": "Ante Bet"
    },
    {
      "slug": "expanding_wild",
      "name": "Expanding Wild"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/rat-royale-b7/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/rat-royale-b7/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/rat-royale-b7/demand/
```

**12-month volume (illustrative):** 0 · **trend:** flat

> Illustrative snapshot — query the live endpoint for current values.

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/rat-royale-b7/
- **Public page:** https://i-gaming.tools/slot-games/rat-royale-b7/
- **Full schema:** https://i-gaming.tools/api/docs/
