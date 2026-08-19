# Chicken Banana

**Provider:** InOut Games

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/chicken-banana-b22/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chicken-banana-b22/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/chicken-banana-b22/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/chicken-banana-b22/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/chicken-banana-b22/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "chicken-banana-b22",
  "name": "Chicken Banana",
  "status": "active",
  "provider": {
    "slug": "inout-games",
    "name": "InOut Games"
  },
  "game_category": "instant_win",
  "rtp_default": "96.00",
  "rtp_variants": [
    {
      "rtp": "96.00",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "",
  "mechanic": "",
  "reels": null,
  "rows": null,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-03-26",
  "themes": [
    {
      "slug": "farm",
      "name": "Farm"
    },
    {
      "slug": "food",
      "name": "Food"
    }
  ],
  "features": [
    {
      "slug": "bonus-game",
      "name": "Bonus Game"
    },
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "guaranteed-win",
      "name": "Guaranteed Win"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/chicken-banana-b22/"
    }
  }
}
```

## Search Demand

`GET /api/v1/slots/chicken-banana-b22/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/chicken-banana-b22/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/chicken-banana-b22/
- **Public page:** https://i-gaming.tools/slot-games/chicken-banana-b22/
- **Full schema:** https://i-gaming.tools/api/docs/
