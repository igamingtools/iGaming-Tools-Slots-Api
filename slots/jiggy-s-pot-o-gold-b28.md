# Jiggy's Pot O' Gold

**Provider:** Push Gaming

> **Note:** Illustrative excerpt — values may differ. Always query the live endpoint for current data, media URLs and demo links.

## Endpoint

`GET /api/v1/slots/jiggy-s-pot-o-gold-b28/`

## Request Examples

### curl

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/jiggy-s-pot-o-gold-b28/
```

### Python (requests)

```python
import requests

r = requests.get(
    "https://i-gaming.tools/api/v1/slots/jiggy-s-pot-o-gold-b28/",
    headers={"Authorization": "Token <your-token>"},
)
data = r.json()
```

### JavaScript (fetch)

```javascript
const r = await fetch("https://i-gaming.tools/api/v1/slots/jiggy-s-pot-o-gold-b28/", {
  headers: { "Authorization": "Token <your-token>" },
});
const data = await r.json();
```

### PHP

```php
$ch = curl_init("https://i-gaming.tools/api/v1/slots/jiggy-s-pot-o-gold-b28/");
curl_setopt($ch, CURLOPT_HTTPHEADER, ["Authorization: Token <your-token>"]);
curl_setopt($ch, CURLOPT_RETURNTRANSFER, true);
$data = json_decode(curl_exec($ch), true);
```

## Illustrative Response

> Media URLs (screenshots, icons, logo) are live CDN/presigned URLs. Request the live endpoint for current values.

```json
{
  "slug": "jiggy-s-pot-o-gold-b28",
  "name": "Jiggy's Pot O' Gold",
  "status": "active",
  "provider": {
    "slug": "push-gaming",
    "name": "Push Gaming"
  },
  "game_category": "video_slot",
  "rtp_default": "96.28",
  "rtp_variants": [
    {
      "rtp": "96.28",
      "variant": "default",
      "is_default": true
    }
  ],
  "volatility": "low",
  "mechanic": "lines",
  "reels": 3,
  "rows": 3,
  "jackpot_type": "fixed",
  "has_bonus_buy": "no",
  "bonus_buys": [],
  "release_date": "2026-07-08",
  "themes": [
    {
      "slug": "irish",
      "name": "Irish"
    }
  ],
  "features": [
    {
      "slug": "free_spins",
      "name": "Free Spins"
    },
    {
      "slug": "money-collect",
      "name": "Money Collect"
    },
    {
      "slug": "prize-symbols",
      "name": "Prize Symbols"
    }
  ],
  "assets": {
    "logo_url": "<live CDN url — request the endpoint>",
    "screenshots": [
      "<live CDN url — request the endpoint>"
    ],
    "demo": {
      "page_url": "https://i-gaming.tools/slot-games/jiggy-s-pot-o-gold-b28/"
    }
  },
  "studio": {
    "slug": "reel-hot-games",
    "name": "Reel Hot Games"
  }
}
```

## Search Demand

`GET /api/v1/slots/jiggy-s-pot-o-gold-b28/demand/`

Trailing-12-month search demand for this slot, with per-country breakdown.

```bash
curl -H "Authorization: Token $TOKEN" \
  https://i-gaming.tools/api/v1/slots/jiggy-s-pot-o-gold-b28/demand/
```

## Links

- **Live endpoint:** https://i-gaming.tools/api/v1/slots/jiggy-s-pot-o-gold-b28/
- **Public page:** https://i-gaming.tools/slot-games/jiggy-s-pot-o-gold-b28/
- **Full schema:** https://i-gaming.tools/api/docs/
